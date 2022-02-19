# GitError-Solutions
### remote: Permission to akshatajagtap19/Python_practice.git denied to Botways.
### fatal: unable to access 'https://github.com/akshatajagtap19/Python_practice.git/': The requested URL returned error: 403

1. ssh-keygen -t ed25519 -C "akshatajagtap19@gmail.com"
2. eval $(ssh-agent -s)
3.  cat ~/.ssh/id_rsa.pub  

Copy key and paste into new shh key on git
1. Refresh repopage and 
 > git remote set-url origin git@github.com:akshatajagtap19/Python_practice.git
3.> git push origin master
