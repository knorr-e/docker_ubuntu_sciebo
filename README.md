### docker_ubuntu_sciebo

Execute in terminal:
 
run in the directory where the Docker file is located
```
docker build -t ubuntu-sciebo -f ./Dockerfile.ubuntu_sciebo .
```
then run container:
```
docker run -it ubuntu-sciebo bash  
```
crontab with sciebo login must first be adapted manually. Later I will also implement this in a direct way


