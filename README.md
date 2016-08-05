# Filenet-Gradle
This is a PoC to learn the usage of Gradle in a project with FileNet

Steps to configure Gradle for a new project:
1. Copy gradle.properties, gradlew and gradlew.bat files at project root
  - The gradle.properties contains content like the proxy configuration
  
2. Copy the wrapper folder containing the gradle-wrapper.jar and gradle-wrapper.properties
  - Gradle-wrapper.properties indicates the distribution to be used
  
3. Go to the path of the project where the bat is created (C:\Users\xxx\IdeaProjects\FilenetUtilities>) and execute it. After the execution, on the view Gradle Projects a new one appears

  :help
  Welcome to Gradle 2.10.
  To run a build, run gradlew <task> ...
  To see a list of available tasks, run gradlew tasks
  To see a list of command-line options, run gradlew --help
  To see more detail about a task, run gradlew help --task <task>
    BUILD SUCCESSFUL
  Total time: 5.754 secs

