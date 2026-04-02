# Day 12 Commands - Jenkins and Maven

## Starting Jenkins (assuming standard installation):
```bash
sudo systemctl start jenkins
sudo systemctl status jenkins
```

## Running a Maven build via Jenkins shell execution:
```bash
mvn clean package
```

## Some common Jenkins related directories:
```bash
/var/lib/jenkins/workspace/     # Where Jenkins runs the builds
/var/log/jenkins/jenkins.log    # Jenkins logs
```
