## Version managers. 
Thease are used to set up virtual environment for development and enables to use any version of choice whithout installing packages on OS in hard way. 

###Java version manager
https://sdkman.io/sdks

```java
sdk list java
sdk install 24.ea.10-open
sdk use java 24.ea.10-open
java -version>
#build package 
mvn clean package

git pull origin master
gcloud init
gcloud config configurations list
 cp /mnt/c/Users/amard/Downloads/settings.xml .
.m2 
cd -

playground #guru
java -version
docker tag 24ff63aff815 singhamardeep341/jaivika:2024
docker push singhamardeep341/jaivika:2024    #without account tag will not allow to push 
mvn clean install

sudo hwclock -s

docker inspect singhamardeep341/jaivika:2024 | grep -i -C 3 port
docker inspect singhamardeep341/jaivika:2024 | grep -i expose 

##NVM (Node Version Manager)
nvm list-remote
nvm install v22.5.1
node-v
##python versions 
https://joachim8675309.medium.com/managing-python-versions-with-pyenv-ddd7882eb39e
python -V
pyenv install 3.12.5
pyenv global 3.12.5
pyenv local 3.12.5
pyenv install --list  # list all versions available 

https://github.com/alanbchristie/PySimple
 docker tag dffbdde124d3 singhamardeep341/pythonbuild:v1

 ---
 https://github.com/kodekloudhub/go-webapp-sample
go run main.go &

docker run -d -p 8000:8000 singhamardeep341/golang:v1