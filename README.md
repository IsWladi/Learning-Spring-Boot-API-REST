# Learning SpringBoot

## Neovim Spring Boot Setup

## Running the API

## Running the Containers

## Identified Issues with the SpringBoot REST API Guide
- If you encounter an error during testing that the main class cannot be found, it's because you need to add the `GreetingControllerTests.java` test. This is because the default test provided by `https://start.spring.io/` does not cover the REST service that is added, and the Spring guide itself does not mention this.

## Java and Maven Environment Variables Example - Linux
``` zsh

# add jdk environment variables
export JAVA_HOME='/opt/jdk-17.0.10'
PATH="$JAVA_HOME/bin:$PATH"
export PATH

# add maven environment variables
export M2_HOME='/opt/apache-maven-3.9.6'
PATH="$M2_HOME/bin:$PATH"
export PATH

```

# References
- [SpringBoot - API REST Build Guide](https://spring.io/guides/gs/rest-service)
- [SpringBoot - API REST Guide GitHub Repository](https://github.com/spring-guides/gs-rest-service)
- [Tutorial - How to Install Java and Maven on Linux](https://www.digitalocean.com/community/tutorials/install-maven-linux-ubuntu)
