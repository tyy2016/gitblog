# Add SSH key :
- check if there is already existed SSH key,if existed,copy and make backup.

*cd ~/.ssh    ls -al*
- if not exist,create SSH key.

*ssh-keygen -t rsa -C "xxxxx@qq.com"*
- copy the id_rsa.pub to setting.

*vim id_rsa.pub   ctrl+a ctrl+c setting ctrl+v*
- OK.


# github upload :
- create a remote repositoies.

*a new repositoies which called pystudy*
- create a local repositoies and the name is same to remote repositoies.

*mkdir pystudy    mv hello.py pystudy/*

*git remote add origin git @github.com:tyy2016/pystudy.git*

*git add .*

*git commit -m "introduction"*

*git push -u origin master*
