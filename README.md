# First Session Code Example


Covered in Session
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
7. Installed Spring Tools 4 add-on from the Eclipse Marketplace under Help
8. Created a Spring Tools Runtime By starting as a Spring API app with the provided default spring tools runtime.
9. Adjusted JDK runtime at workspace setup explicitly by directory
10.Ran the Spring API we downloaded in Eclipse via the IDE 'Run As' => 'Spring Boot App Option' and stop it with the IDE provided red button on the console top right of the console window.