# docker-jenkins-standalone

## What is it?

It is a project to run Jenkins(https://jenkins.io) in docker by :


## How to use?

```
docker run -d -p 8080:8080 -v $(pwd)/jenkins:/root/.jenkins/ --name my-jenkins volnet/jenkins-standalone
```

You can also use this ( recommends ):

```
git clone https://github.com/volnet/jenkins-standalone.git
cd jenkins-standalone/

./jenkins_start.sh

# stop it by
# ./jenkins_stop.sh
```
