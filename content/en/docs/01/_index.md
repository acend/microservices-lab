---
title: "1. Getting Started"
weight: 1
sectionnumber: 1
---

## Introduction


### Requirements

Following Software is required to run the labs:

* Java 11, Maven, Git
* Installed Docker Engine and Docker-Compose supporting at least version 3 of the compose format[^1].
* Integrated Development Environment IDE. We do recommend [IntelliJ IDEA](https://www.jetbrains.com/idea/).
  * Or any other editor you are comfortable with for editing Java files.

The following access must be available:

* Lab Pages: https://microservices-lab.training.acend.ch/docs/
* Docker Registries: [docker.io](https://docker.io) and [quay.io](https://quay.io)
* Source Repositories: [github.com](https://github.com)
* Various web resources: like [quarkus.io](https://www.quarkus.io/), [microprofile.io](https://www.microprofile.io/), Google Drive, ...
* Public maven repositories like maven-central.


### Source-Code for Labs

Writing the labs from scratch would take too much time. We provide source-code to start with for the labs:

* Git Repository: {{% param "lab_git_repo" %}}
* Base Directory: {{% param "lab_code_basedir" %}}

You have to checkout this repository and switch to the corresponding lab source-code folder. You can open the `{{% param "lab_code_basedir" %}}` in your IDE.


### Solution Repository

Complete code for all labs can be found here:

* Git Repository: {{% param "solution_git_repo" %}}
* Base Directory: {{% param "solution_code_basedir" %}}


## Using the Hands-On Labs

In the following labs you will find sections marked with the following blocks.


### Hints

We usually provide help for a task you have to complete. For example if you have to implement a method you most likely find the solution in a _Task Hint_ like this one:

{{% details title="Task Hint" %}}
Your method should look like this:

```java
public class HelloWorldApp {
  public static void main(String[] args) {
    System.out.println("Hello World!");
  }
}
```
{{% /details %}}


### No changes needed

This means that the implementation of this section is time-consuming and have already been implemented to focus on other details. The changes made are described, and you can read the section.

{{% whenLabDuration "four-hours" %}}
{{% alert title="Limited lab duration" color="duration" %}} {{% param "four-hours-text" %}} {{% /alert %}}
{{% /whenLabDuration %}}


### Advanced Content

This means that this section is optional and we do not require you to complete the section.


{{% whenSectionType "optional" %}}
{{% alert title="Optional Section" color="optional" %}} {{% param "optional-text" %}} {{% /alert %}}
{{% /whenSectionType %}}

[^1]: Compose file: https://docs.docker.com/compose/compose-file/
