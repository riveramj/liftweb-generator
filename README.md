# Liftweb Generator 

Lift projects require a number of folders and files that must be present for a basic project.

The generator will ask some basic questions and then create the files and folders required.


Questions it asks (with sample answers)

1. **Enter the path for the new lift project:** /path/that/exists/
1. **what is the app name:** foo
1. **what is the app organization [com.example]:** com.foo
1. **what is the starting version [0.1-SNAPSHOT]:** 1
1. **what scala version do you want to use [2.11.7]:** 2.11.7

then it’ll create a
* build.sbt
* Boot.scala
* Paths.scala

and populate the values given as needed.

it also creates the structure:
* project
* src/main/scala/bootstrap/liftweb/
* src/main/scala/$orgStructure/util
* src/main/resources/props
* src/main/webapp/WEB-INF
* src/main/webapp/templates-hidden
* src/main/webapp/static
