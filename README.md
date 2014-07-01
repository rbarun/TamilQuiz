TamilQuiz
=========

<!--
  mvn archetype:generate \
 -DgroupId=org.neti.onlinequiz \
 -DartifactId=TamilQuiz \
 -DarchetypeArtifactId=maven-archetype-webapp \
 -DinteractiveMode=false
-->

add java under src/main


    <plugins>
       <plugin>
           <groupId>org.apache.maven.plugins</groupId>
           <artifactId>maven-compiler-plugin</artifactId>
           <version>2.3.1</version>
           <configuration>
               <source>1.6</source>
               <target>1.6</target>
           </configuration>
       </plugin>
    </plugins>






    git init
    git add .
    git commit -m "first commit"
    git remote add origin https://github.com/rbarun/TamilQuiz.git
    git pull -u origin master
    git push -u origin master

.gitignore
target/
.classpath
.project
.classpath
.project
.settings/



