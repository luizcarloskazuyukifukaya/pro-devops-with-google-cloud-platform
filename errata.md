# Errata for *Book Title*
On **page xx** [Summary of error]:
 
Details of error here. Highlight key pieces in **bold**.

***
On **page 120, 122** [Jenkins Docker image file path correction]:
 
The Jenkins Docker image file should be **jenkins/jenkins:lts**. For details of the file, please refer to [https://hub.docker.com/r/jenkins/jenkins/](https://hub.docker.com/r/jenkins/jenkins/).

```
...
spec:
  containers:
  - name: master
    image: **jenkins/jenkins:lts**
```
***
***
On **page 129** [Jenkins username correction]:
 
The actual Jenkins username should be **"jenkins"** instead of "Jenkins".
***
