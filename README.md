---
## Step: 1 Pull file from the git repository 
---
**Dashboard ==> Plugin** 

> maven 
git
![image](https://user-images.githubusercontent.com/66588814/169749693-fc050bfa-4c5b-4215-8aee-c41f605d2ca3.png)
![image](https://user-images.githubusercontent.com/66588814/169749987-a18eac99-76c5-4ea7-8d33-de9300e4c042.png)

### Make a Freestyle Project 
**Dashboard ==> sample-maven-1** 
Add git URL
![image](https://user-images.githubusercontent.com/66588814/169750367-573d1c22-3313-4103-9410-2b27f7920bee.png)
Check wit console  they provide workspace link 
![image](https://user-images.githubusercontent.com/66588814/169751085-12c1722c-79ba-4a1b-bfb8-0355c5d4fd53.png)

---
## Step: 2 Build a Maven jar file 
---
`Under this we install Maven and make a build of maven `
Go To **Dashboard ==> Global Tool Configuration** 
![image](https://user-images.githubusercontent.com/66588814/169751741-8350e3ac-a4b1-4885-a20e-fd09a4dd0036.png)
Go To **Dashboard ==> sample-maven-test1==> Configure**
![image](https://user-images.githubusercontent.com/66588814/169752304-3d271b95-f0a6-4f87-a901-f201a112a648.png)

**You can check the jar file on the given link on the console output** 
![image](https://user-images.githubusercontent.com/66588814/169752541-b6de9583-ec9d-48b1-829d-aad5c13b3fbb.png)

---
## Step: 3 Write Unit-Test to test  a code quality 
---
Go To **Dashboard ==> sample-maven-test1==> Configure**
![image](https://user-images.githubusercontent.com/66588814/169753293-158b42e0-a6ef-4fe0-9a86-37e4b4875aab.png)

---
## Step: 4 Deploy Artifact to local 
---
Go To **Dashboard ==> sample-maven-test1==> Configure**
![image](https://user-images.githubusercontent.com/66588814/169753504-ff5304e8-2d4d-4599-aa80-41617af0aead.png)

---
## Step: 5 Show UT graph on Jenkins
--- 
Go To **Dashboard ==> sample-maven-test1==> Configure**
![image](https://user-images.githubusercontent.com/66588814/169753781-8a943c9f-3c3d-4207-94a8-4a1dcc8c8f28.png)







## simple-java-maven-app

This repository is for the
[Build a Java app with Maven](https://jenkins.io/doc/tutorials/build-a-java-app-with-maven/)
tutorial in the [Jenkins User Documentation](https://jenkins.io/doc/).

The repository contains a simple Java application which outputs the string
"Hello world!" and is accompanied by a couple of unit tests to check that the
main application works as expected. The results of these tests are saved to a
JUnit XML report.

The `jenkins` directory contains an example of the `Jenkinsfile` (i.e. Pipeline)
you'll be creating yourself during the tutorial and the `scripts` subdirectory
contains a shell script with commands that are executed when Jenkins processes
the "Deliver" stage of your Pipeline.
