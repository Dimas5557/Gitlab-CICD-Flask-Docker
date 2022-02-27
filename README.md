To check my test task you need:
1) You need install gitlab-runner on your host(i used my local machine)
2) You need to provide all rights on 1 /var/run/docker.sock
                                     2 directories which will contain project files ("/home" in my case)
3)You need to run our pipeline in gitlab and click on deploy bottom 
4)You can check running docker container on your machine 
5)Check localhost:80 (also you should release port 80, you can check it with:"netstat -lnp")
