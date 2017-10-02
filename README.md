# Description

This is a sample project which is indented to demonstrade the behavior reported in [#10470](https://github.com/spring-projects/spring-boot/issues/10470).

To run:

```
$ git clone https://github.com/luchob/boot-issue-10470.git
$ cd boot-issue-10470/
$ ./gradlew bootRun
Starting a Gradle Daemon, 1 incompatible Daemon could not be reused, use --status for details
:compileJava
:processResources
:classes
:findMainClass
:bootRun
14:38:52.823 [main] DEBUG org.springframework.boot.logging.ClasspathLoggingApplicationListener - Application failed to start with classpath: [...]
<==========---> 80% EXECUTING
```
