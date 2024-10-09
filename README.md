# Kotlin Starter Boilerplate
A minimal Kotlin Boilerplate

Kotlin Init will generate this boilerplate for a kotlik application type, for more types review the documentation, in
[gradle types](https://docs.gradle.org/current/userguide/build_init_plugin.html#supported_gradle_build_types)

## Common Gradle Types
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
### Gradle Common commands
```sh
# Run the application
gradle run

# Run tests and checks
gradle check

# List all tasks
gradle tasks

# Clean the build directory
gradle clean

# Clean and build the project
gradle clean build

# List project dependencies
gradle dependencies

# Execute a specific task (e.g., fooTask)
gradle :fooTask

```

For a complete list of commands check [Gradle CLI Documentation ](https://docs.gradle.org/current/userguide/command_line_interface.html)

## Gradle completition 
To enhance your command-line experience with Gradle, you can enable autocomplete for Bash and Zsh. This feature provides rapid syntax completion for Gradle CLI switches and common properties.

### Gradle completition in macOS
To set uo Gradle completition on macOS, follow these steps:
1. Install the Gradle completition tool using Homebrew:
```sh
brew install gradle-completition
```

2. Add the following line for the completition scripts:
```sh
echo '[[ -r "/usr/local/etc/profile.d/bash_completion.
sh" ]] && . "/usr/local/etc/profile.d/bash_completion.sh"' >> ~/.bash_profile
```

3. Load the changes to your Bash profile:
```sh
source ~/.bash_profile
```

### Gradle completition for Linux

For *Nix systems, you can manually download it and execute it.
```sh
mkdir $HOME/bash_completion.d
curl -LA gradle-completion https://edub.me/gradle-completion-bash -o $HOME/bash_completion.d/gradle-completion.bash
```
