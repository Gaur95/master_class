# master_class
## topics - Linux ,Github , jenkins , AWS
### docker installation
```
sudo apt update ; sudo apt install docker.io -y
```
```
sudo chmod 777 /var/run/docker.sock
```

### jenkins
### install jenkins in docker 
```
docker run -itd --name jenkins -v v1:/var/jenkins_home -v /run/docker.sock:/run/docker.sock -v /usr/bin/docker:/bin/docker  -p 8080:8080 -p 50000:50000 jenkins/jenkins
```
### after installation 
```
http://your_public_IP:8080
```
```
docker logs jenkins
```
```
https://github.com/Gaur95/test12.git
```
### jenkins exe. shell
```
docker build -t mypro .
docker run --name mycon -p 80:80 mypro
```
