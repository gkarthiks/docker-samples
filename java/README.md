## Hellow world! Docker + Java + Tomcat
---

Here we are going to use the existing `tomcat` war file which is comporised of `Hello.java` class file as a *Servlet* and JSP pages.

## Build
> docker build -t java-docker .

## Run

> docker run -p 8080:8080 java-docker

## Verify

Open browser and hit `http://localhost:8080/sample`
