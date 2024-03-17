# playbook-install-jenkins

sesuaikan variable jenkins_port dan jenkins_tag pada file install-jenkins.yaml

```

ansible-playbook install-jenkins.yaml -vvvv
```


```
jenkins as container
docker run -u root --name jenkins-dev -d -v /data_jenkins:/var/jenkins_home -p 8088:8080 jenkins/jenkins:latest
```
