# GitError-Solutions
### remote: Permission to akshatajagtap19/Python_practice.git denied to Botways.
### fatal: unable to access 'https://github.com/akshatajagtap19/Python_practice.git/': The requested URL returned error: 403
Enter the following command on git bash
>ssh-keygen -t ed25519 -C "akshatajagtap19@gmail.com"                                            
>eval $(ssh-agent -s)                                                                                           
>cat ~/.ssh/id_rsa.pub                              

Copy key and paste into new shh key on git
1. Refresh repopage and 
 > git remote set-url origin git@github.com:akshatajagtap19/Python_practice.git
> git push origin master
