# First Session Code Example

## Notes on Java
If you're new to Java, haven't done it in a while and need a refresher, and absorb things well by reading, I'd suggest the official Oracle tutorials as they're quite good, but one of the others may more suit your style.

- [Official Oracle Java Tutorial](https://docs.oracle.com/javase/tutorial/)
- [Geek 4 Geeks Java Tutorial](https://www.geeksforgeeks.org/java/)
- [Java “Back to Basics” Tutorial](https://www.baeldung.com/java-tutorial)
- [W3Schools Java Tutorial](https://www.w3schools.com/java/) (Comes with a web based IDE to run your changes to the example code!)

There are many introductory Java materials on youtube if you prefer videos.

## Tools to install:

- [JDK 20](https://download.oracle.com/java/20/latest/jdk-20_windows-x64_bin.exe) (Any version of Java 11+ will do for our purposes. This is a Java 20 direct link to an installer. Please remember where you install it as that will be important later.)
- [Eclipse IDE for Java Developers](https://www.eclipse.org/downloads/packages/release/indigo/r/eclipse-ide-java-developers)
- [Maven](https://phoenixnap.com/kb/install-maven-windows)

## Session Notes:

### Covered in Session 1

1. Installing Java
   Links to options available in #notes-resources channel in discord and also in the Study Room 1 chat.
   note: Some people chose 17 and some chose 20. so note the config change in the pom.xml java.version property attribute value.
   Java 17
   ```
   <properties>
   	<java.version>17</java.version>
   </properties>
   ```
   Java 20
   ```
   <properties>
   	<java.version>20</java.version>
   </properties>
   ```
2. Downloading latest Maven Binaries and add them to the system CLASSPATH
3. Links in discord Study Room 1 Chat
4. Run a 'clean' Maven build with 'mvn clean'
5. Run the Spring API directly from the zipped https://start.spring.io template using the spring provided run command 'mvn spring-boot:run' and checked our app was up by hitting the spring actuator endpoints at http://localhost:8080/actuator/info and getting a JSON Response {"status":"UP"} via HTTP GET by entering the address in our browser of choice.
6. Installed Eclipse
7. Created a workspace folder independent of the code
8. Imported the Maven project as a Maven project in Eclipse
9. Installed Spring Tools 4 add-on from the Eclipse Marketplace under Help
10. Created a Spring Tools Runtime By starting as a Spring API app with the provided default spring tools runtime.
11. Adjusted JDK runtime at workspace setup explicitly by directory
    10.Ran the Spring API we downloaded in Eclipse via the IDE 'Run As' => 'Spring Boot App Option' and stop it with the IDE provided red button on the console top right of the console window.
