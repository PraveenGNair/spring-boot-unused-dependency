# Maven Dependency Plugin with Spring boot

## Overview
>The usage of plugin in maven project is described in [blog](https://medium.com/@prgnr173/quick-find-unused-maven-dependencies-c32ece492709).
>Maven dependency plugin helps in analyzing the used and unused depedencies in maven project.
>Detailed info about plugin can be found on the [docs.](https://maven.apache.org/plugins/maven-dependency-plugin/)

## Run the command

- Maven dependency tree for all dependencies

`$ mvn dependency:tree`

- Now with Maven analyze tells used/unused dependencies

`$ mvn dependency:analyze`


## Run Application

`$ mvn spring-boot:run`