# Cloud Native Workshop
Cloud Native Application development with Spring and Cloud Foundry. Join Pivotal and Perficient for a full-day hands-on workshop to introduce key concepts in modern cloud native application development and delivery. This workshop will introduce concepts of cloud-native and Spring application development along with Pivotal Cloud Foundry.  The labs will leverage Spring Boot and Actuator, Spring Data, and other Spring projects. 

[Registration link](https://pivotal.io/event/cloud-native-workshop/stl)

## Agenda

Time | Session
---- | -------
8:30 AM - 9:00 AM | _Registration and Breakfast_
9:00 AM - 9:30 AM | _Session 1: Cloud Native Architectures & Frameworks_ (Steve)
9:30 AM - 11:30 AM | _Session 2: Pivotal Cloud Foundry Overview with Labs*_ (Chris)
11:30 AM - 12:00 PM | _Session 3: Spring Boot and Actuator with Labs*_ (Sharath)
12:00 PM - 1:00 PM | _Working Lunch with Guest Speaker from Perficient_ (Dave)
1:00 PM - 2:00 PM | _Session 4: Spring Data on Cloud Foundry with Labs*_ (Steve)
2:00 PM - 3:00 PM | _Session 5: Spring Cloud Services on Cloud Foundry_ (Navjot)
3:00 PM - 4:00 PM | _Session 6: Route Services with Apigee with Labs*_ (Navjot)
4:00 PM - 4:30 PM | _Wrap-up, Q&A, Course evaluation_

_*See [Course Materials](#course-materials) section below for slides and labs_

This is a _loose_ schedule for the day. We will adjust as necessary based on our pace through the material.

The lectures for this class are intentionally very light and are only intended to set the stage for the hands-on labs.
The overwhelming majority of our time will be spent engaging with the technology directly!

## Getting started

**Prerequisites**

Start by downloading and installing the appropriate prerequisite tools.
- [Cloud Foundry CLI](https://goo.gl/M0pH4i) to interact with a cloud foundry instance
- [Apache Maven](http://info.pivotal.io/HI002010A6ZlRJR1NeU00eC) to build labs using Maven
- [Gradle](https://services.gradle.org/distributions/gradle-3.1-all.zip) to build labs using Gradle
- [Git Client](https://git-scm.com/downloads) to clone Github repo or download and unzip
- An IDE, like [Spring Tool Suite](https://spring.io/tools/sts/all) or [IntelliJ IDEA](https://www.jetbrains.com/idea/download/)
- [Java SE Development Kit](http://info.pivotal.io/n0I60i3021AN0JU0le10CRR)

**Download materials**

Next, download the course materials.  This can be accomplished either through the GitHub website by downloading a repository zip and unzipping locally, or if you have Git installed, use the following commands:

```
$ git clone https://github.com/cbusch-pivotal/stl-cloud-native-spring-workshop
$ cd stl-cloud-native-spring-workshop/
$ git fetch --all
```

## Course Materials

#### _Session 1: Cloud Native Architectures & Frameworks_ [(Slides)](session_01/Session_01-Cloud_Native_Architectures_and_Frameworks.pptx)

#### _Session 2: Pivotal Cloud Foundry Overview_ [(Slides)](session_02/Session_02-Pivotal_Cloud_Foundry-The_Cloud_Native_Platform.pptx)
  - [Lab 1 - From Zero to Pushing Your First Application](session_02/lab_01/lab_01.adoc)
  - [Lab 2 - Binding to Cloud Foundry Services](session_02/lab_02/lab_02.adoc)
  - [Lab 3 - Scaling Applications](session_02/lab_03/lab_03.adoc)
  - [Lab 4 - Monitoring Applications](session_02/lab_04/lab_04.adoc)

#### _Session 3: Spring Boot and Actuator_ [(Slides)](session_03/Session_03-Spring_Boot_and_Actuator.pptx)
  - [Lab 5 - Introspection, Monitoring, and Metrics using Spring Boot Actuator](session_03/lab_05/lab_05.adoc)

#### _Session 4: Spring Data on Cloud Foundry_ [(Slides)](session_04/Session_04-Spring_Data.pptx)
  - [Lab 6 - Build a Hypermedia-Driven RESTful Web Service with Spring Data REST](session_04/lab_06/lab_06.adoc)
  - [Lab 7 - Leveraging Spring Cloud Connectors for Service Binding](session_04/lab_07/lab_07.adoc)

#### _Session 5: Spring Cloud Services on Cloud Foundry_ [(Slides)](session_05/Session_05-Spring-Cloud-Services.pptx)
_Extra credit - labs can be done on your own!_
  - [Lab 8 - Binding Spring Cloud Services](session_05/lab_08/lab_08.adoc)
  - [Lab 9 - Service Registry](session_05/lab_09/lab_09.adoc)
  - [Lab 10 - Config Server](session_05/lab_10/lab_10.adoc)
  - [Lab 11 - Circuit Breaker Dashboard](session_05/lab_11/lab_11.adoc)

#### _Session 6: Route Services with Apigee_ [(Slides)](session_06/Session_06_Route_Services.pdf)
  - [Lab 12 - PCF Route Service with Apigee](session_06/lab_12/lab_12.adoc)
  - [Lab 13 - Apigee DevJam](session_06/lab_13/lab_13.adoc)

#### _Wrap-up, Q&A, Course evaluation_ [(Slides)](session_wrapup/Session_Wrap-up.pptx) [(Evaluation)](http://evaluation.lnk)

## Instructors
- Chris Busch, Pivotal Platform Architect, cbusch@pivotal.io
- Navjot Sagoo, Pivotal Platform Architect, nsagoo@pivotal.io
- Sharath Sahadevan, Pivotal Platform Achitect, ssahadevan@pivotal.io
- Dave Stockmann, Perficient Principle Architect, dave.stockmann@perficient.com
- Steve Womack, Pivotal Platform Architect, swomack@pivotal.io

