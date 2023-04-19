

```console
docker exec -it -u root d3cc4f5c9056 bash 
````

```console
chmod 777 /var/run/docker.sock
```

#### Instalar plugin docker
#### Instalar plugin Nodejs
#### Instalar plugin Kubernetes e Kubernetes CLI

Ir em 
´´´Manage jenkins´´´ 
Selecionar Nodejs 16.16.0,  e em 
´´´Global npm packages to install´´´
colocar 
´´´npm install´´´


## update

http://updates.jenkins-ci.org/download/war/

```console
cd var/jenkins_home/
```
```console
wget http://updates.jenkins-ci.org/download/war/2.401/jenkins.war
```
```console
java -jar enkins.war
```

