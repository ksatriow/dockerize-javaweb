# Dockerize Image for Java Webapp
## _Java Webapp using build-tools Apache Maven_

![Apache Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white)

Explain how to building docker images for Java Webapp projects using Apache Maven build-tools.

## Step

- Create project using Apache Maven
- Deployment using Tomcat Web Server
- Build Docker Images
- Running Web Application

## Tech

Using tools, software and operating system:

- ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
- ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)
- ![Apache Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white)
- ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)


## Installation

For Bash script:

```sh
mvn archetype:generate \
-DgroupId=com.maryanto.dimas.udemy \
-DartifactId=docker-javaweb \
-Dversion=1.0.0-release \
-DarchetypeCatalog=internal \
-DarchetypeGroupId=org.apache.maven.archetypes \
-DarchetypeArtifactId=maven-archetype-webapp
```

For Powershell script:

```powershell
mvn archetype:generate `
-DgroupId='com.maryanto.dimas.udemy' `
-DartifactId='docker-javaweb' `
-Dversion='1.0.0-release' `
-DarchetypeCatalog='internal' `
-DarchetypeGroupId='org.apache.maven.archetypes' `
-DarchetypeArtifactId='maven-archetype-webapp'
```

## Reference
[Udemy](https://www.udemy.com/course/docker-pemula-sampai-mahir/)


## License

MIT