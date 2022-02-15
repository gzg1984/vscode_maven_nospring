# vscode_maven_nospring
## system requirement
```
apt install maven2
```
    - maven has its seperated java runtime dependency
    - maven2 dependent java5 and maven3 dependent java7
    - no matter what is your project use and what you have installed, maven  requries jre7
    - if you dont't install maven , you cannt do anything depend on maven like dependency analyze.
## Edit ~/.m2/setting.xml
    - use alternative source to download package to solve this problem
```
    The plugin 'org.apache.maven.plugins:maven-help-plugin' does not exist or no valid version could be found
```
## manual compile
```
mvn compile
```

## Vscode requriement
- tomcat for java
- to use it:
    - generate war from current folder
    - add tomcat server like "/home/zhiganggao/apache-tomcat-8.5.75/"
    - if you use no root remote IDE, you will not allowed to use /opt/apache-tomcat directly.
    - so use tomcat in your home folder instead

## Deploy access
- http://localhost:8080/vscode_maven_nospring/src/main/webapp/

## NO
- nospring.war will be create by mvn package