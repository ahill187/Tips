Open Intellij
File -> Project Structure -> Artifacts
Click on the "+" sign
JAR -> From modules with dependencies
Change manifest file from ".../java" to ".../resources"
Click "Apply"
Build -> Build Artifacts

From UNIX bash:

```
$ cd {Your project directory}/out/artifacts/{Your project name}_jar/
$ java -jar {Your_project_name}.jar
```
