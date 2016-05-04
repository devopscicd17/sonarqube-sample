Sonar Qube Code analysis 
==========================================

Sonar is an open source web-based application to manage code quality,Architecture and design, comments, duplications, unit tests, complexity, potential bugs
 and coding rules. Developed in Java and can cover projects in Java, Java script...etc.

It's very efficient and offering good visual reporting, easy steps to resolve the reported issues and coding standards.


<b>How to use and configure</b>
<hr/>

Its devided to two parts sonar qube server and build.

Sonar qube server :

Download: <a href=http://www.sonarsource.org/">Sonar</a>

<p>You must to have a Sonar server running and define it in sonar.host.url parameter in choosed build system. The default Sonar URL, http://localhost:9000 

Running Server: <extracted sonarqube-5.5 zip>/bin/<choose respective OS folder/StartSonar.XXX

access http://localhost:9000, which will show the UI. </p>

Sonar Analysis on respective project and builds

<b>Maven:</b> Its very easy to run sonar analysis using maven

```
	mvn sonar:sonar
```

after the successfull build check the sonar report by accessing the sonar qube server url http://localhost:9000

<b>Gradle:</b> Go throught the build.gradle file for gradle.

```
	gradle sonar
```

<b>Ant:</b> Go through the build.xml file for the ant.

```
	ant sonar
```

 