# desktop-java-simple

# Developer Workspace

[![Contribute](http://beta.codenvy.com/factory/resources/codenvy-contribute.svg)](http://beta.codenvy.com/f?id=omriatu352kkthua)

# Recipe

FROM [codenvy/ubuntu_jdk8](https://hub.docker.com/r/codenvy/ubuntu_jdk8/)

# Commands

| #       | Command           | 
| :------------- |:------------- |
| 1      | `mvn -f ${current.project.path} clean install && java -jar ${current.project.path}/target/*.jar` |

# App output

App output is streamed into a console. Note that if your app expects user input, do not use command but execute jars in the terminal directly.
=======
# java-playground
A simple java project to try things
This project was generated in a codenvy workspace and mainly used to see how I can try things without the need of a full blown java development environment on my local machine.
This HelloWorld project is the default java project that is created when you add a java task in the workspace.

Instructions to link the Codenvy workspace with git hub come from https://seerocode.github.io/Upload-Codenvy-Project-To-Github/

Note that step 8 states "Go back to Codenvy and initialize a repository by going to Git > Intitialize Repository" but the option was grayed out in my case as the default project was already a git project created as part of the java task by codeenvy

