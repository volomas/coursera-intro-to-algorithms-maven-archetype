# README #
This is maven archetype that you can use to create a maven project for your assignments on ["Introduction to Algorithms" (Coursera)](https://www.coursera.org/learn/introduction-to-algorithms/).

Usage:
1.) Install archetype into your local repository:

```
cd coursera_algs
mvn install

```
2.) Generate a project's skeleton:

```
mvn archetype:generate -DarchetypeGroupId=vmas -DarchetypeArtifactId=coursera_algs -DarchetypeVersion=1.0 -DgroupId=whatever -Dversion=1.0 -Dpackage=whatever -DartifactId=<name_of_assignment>

```
3.) Jump in newly created project and work on assignment. To package a zip for submission to grader, use:

```

mvn package

```
* Note: Zip file will be in target folder
