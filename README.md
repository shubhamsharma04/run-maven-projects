# run-maven-projects
A single repository which contain instructions for running my maven based projects on local machine

# Configurations and versions of various systems in my machine :-
  - java version "1.8.0_111" 64 bit (jdk provided by oracle and not openjdk)
  - maven version 3.3.9
  - Eclipse Neon EE with -Xms256m -Xmx1024m set in eclipse.ini file
  - Linux Mint 18.1 with Kernel: 4.4.0-53-generic x86_64 (64 bit)
  - Java and maven set in PATH variable. JAVA_HOME, M2_HOME set in bashrc
  
  1) To download Oracle jdk 8 visit http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
  2) To download Apache Maven visit https://maven.apache.org/download.cgi
  3) To download Eclipse visit http://www.eclipse.org/downloads/eclipse-packages/
  4) Download/clone my project onto your local system.
  5) Unzip the file and goto the directory 
  6) Execute mvn clean install. Most of my projects use maven shade plugin to build an uber jar, so the size of the jar might be really yuge.
  7) If there are any configurations to be set, set them in prperties file inside resources.
  8) Either execute the jar using java -jar name-of-jar.jar or import it in eclipse as a maven project.
  9) That's it.
