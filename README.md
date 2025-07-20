# Creating a maven solo and multi module project
This project explains basic maven java based project.

## To skip test use the below flag
% mvn -Dmaven.test.skip=true package

## Create multi module project steps
* first add <packaging>pom</packaging> in the parent project
* generate a new project with the below command  
% mvn archetype:generate -DgroupId=org.maghi711 -DartifactId=common-util
* you should now see a new module with name common-util being added in the parent project
