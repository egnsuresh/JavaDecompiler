# JavaDecompiler
how to decompile .class file back to .java file to see source code

### 0. Install Java and set the Path if not yet done 
### 1. Download the java-decompiler.jar file
### 2. Syntax and Example
java -cp <java-decompiler.jar file full path> org.jetbrains.java.decompiler.main.decompiler.ConsoleDecompiler -hdc=0 -dgs=1 -rsy=1 -lit=1 <.class file with full path> <destination directory>

java -cp "C:\Downloads\java-decompiler.jar" org.jetbrains.java.decompiler.main.decompiler.ConsoleDecompiler -hdc=0 -dgs=1 -rsy=1 -lit=1 "C:\JavaPrograms\dotClassFiles\Hello.class" "C:\JavaPrograms\dotJavaFiles"
