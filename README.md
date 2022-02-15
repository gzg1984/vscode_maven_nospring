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