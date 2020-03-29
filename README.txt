from web : https://jenkins.io/doc/book/installing/
First, execute run runner.sh
then execute runner-sec.sh

In the first time, need to take from the first container the password in:
/var/jenkins/secrets/initialAdminPassword
with the command :
docker exec -it  jenkins-blueocean bash