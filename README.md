### Part 1 - Install And Use Docker
1. [Install Git Command Line Interface](https://curriculeon.github.io/Curriculeon/lectures/version-control-systems/git/installation/content.html)
2. [Install Java](https://curriculeon.github.io/Curriculeon/lectures/java/installation/content.html)
3. [Install Maven](https://curriculeon.github.io/Curriculeon/lectures/java/build-automation/maven/installation/content.html)
4. [Install Docker](https://curriculeon.github.io/Curriculeon/lectures/containerization/docker/installation/content.html)
5. [Install Docker (Windows 7)](https://curriculeon.github.io/Curriculeon/lectures/containerization/docker/installation-windows7/content.html)
6. [Containerize a Jar](https://curriculeon.github.io/Curriculeon/lectures/containerization/docker/containerizing-jars/content.html)
7. [SSH Into Docker Container](https://curriculeon.github.io/Curriculeon/lectures/containerization/docker/ssh-into-container/content.html)


### Part 2 - Install And Configure Jenkins
1. [Install Jenkins](https://curriculeon.github.io/Curriculeon/lectures/ci-cd/jenkins/installation/content.html)
2. [Create Jenkins Command Line Registry](https://curriculeon.github.io/Curriculeon/lectures/ci-cd/jenkins/create-commandline-registry/content.html)
3. [Disable Jenkins Security Use](https://curriculeon.github.io/Curriculeon/lectures/ci-cd/jenkins/disabling-security-use/content.html)
4. [Install Jenkins Plugin - Convert To Pipeline](https://curriculeon.github.io/Curriculeon/lectures/ci-cd/jenkins/install-plugin-convert-to-pipeline/content.html)
5. [Install Jenkins Plugin - Docker](https://curriculeon.github.io/Curriculeon/lectures/ci-cd/jenkins/install-plugin-docker-dependencies/content.html)
6. [Install Jenkins Plugin - ShiningPanda](https://curriculeon.github.io/Curriculeon/lectures/ci-cd/jenkins/install-plugin-shiningpanda/content.html)
7. [Install Jenkins Plugin - Maven Pipeline](https://curriculeon.github.io/Curriculeon/lectures/ci-cd/jenkins/install-plugin-maven-pipeline/content.html)
8. [Jenkins Environment Configuration - Docker Integration](https://curriculeon.github.io/Curriculeon/lectures/ci-cd/jenkins/docker-integration/content.html)

### Part 3 - Creating Pipeline
1. [My First Maven Pipeline](https://curriculeon.github.io/Curriculeon/lectures/ci-cd/jenkins/my-first-maven-pipeline/content.html)
	* Create a Jenkins pipeline which
		1. Creates [pulls a docker image with `Git`, `Java` and `Maven` installed](https://hub.docker.com/r/jamesdbloom/docker-java8-maven)
		2. `git clones` [a maven Application](https://github.com/curriculeon/jenkins.docker.maven_java-fundamentals)
		3. `.jar`s the cloned maven application.
		4. runs JUnit tests and ignore failures on `.jar` in container by leveraging command below
			* `mvn package -Dmaven.test.failure.ignore=true`
		5. ensure output of build is displayed by Jenkins


### Part 4 - Passing Test Cases
1. [Java Developer Notes](./README-javadev.md)


### Part 5 - Triggering Pipeline With Passing Tests
