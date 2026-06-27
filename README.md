# CI/CD Pipeline using Jenkins, Maven, Nexus & Apache Tomcat

This project demonstrates a CI/CD pipeline where Jenkins builds a Java web application using Maven, uploads the generated WAR artifact to a Nexus Repository Manager, and deploys the application to Apache Tomcat.

The project showcases Continuous Integration, artifact management, and application deployment on a Linux server.

# Tech Stack

| Component           | Technology               |
| ------------------- | ------------------------ |
| Operating System    | Amazon Linux              |
| Version Control     | Git                      |
| Repository          | GitHub                   |
| CI Tool             | Jenkins                  |
| Build Tool          | Maven                    |
| Artifact Repository | Nexus Repository Manager |
| Application Server  | Apache Tomcat            |
| Language            | Java                     |
| Artifact            | WAR                      |

# Architecture
               GitHub
                  │
                  ▼
             Jenkins Job
                  │
          mvn clean package
                  │
                  ▼
            WAR Artifact
                  │
                  ▼
      Nexus Repository Manager
                  │
                  ▼
          Apache Tomcat Server
                  │
                  ▼
       Java Web Application
