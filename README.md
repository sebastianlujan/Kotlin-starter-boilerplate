# Kotlin Starter Boilerplate
A minimal Kotlin Boilerplate

Kotlin Init will generate this boilerplate for a kotlik application type, for more types review the documentation, in
[gradle types](https://docs.gradle.org/current/userguide/build_init_plugin.html#supported_gradle_build_types)

<br>
The most commons are:

| Type | Description |
------ | ----------------------------- |
| basic | A basic, empty, Gradle build |
| pom | Converts Maven to Gradle |
| kotlin-application | A command-line application implemented in Kotlin/JVM |
| kotlin-gradle-plugin | A Gradle plugin implemented in Kotlin/JVM |
| kotlin-library | A Kotlin/JVM library |

## Gradle Commands
### Init

```sh
gradle init --type kotlin-application --dsl kotlin

# for a basic gradle project:
gradle init --type basic --dsl kotlin
```
## Gradle Common commands
```sh
gradle run
gradle check
gradle tasks
gradle clean
gradle clean build
gradle dependencies

# execute the task :fooTask
gradle :fooTask
```

[gradle CLI ](https://docs.gradle.org/current/userguide/command_line_interface.html)

