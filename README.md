A simple real-time chatroom application built using Spring Boot and WebSocket. This project demonstrates basic real-time communication capabilities between users in a chatroom environment.

Features
Real-time messaging
Multi-user support
WebSocket-based communication
Lightweight Spring Boot setup
Prerequisites
Before running the project, make sure you have the following installed:

Java 8+ (Ensure JAVA_HOME is set correctly)
Maven (For building and running the Spring Boot application)

How to Run the Project

1. Clone the Repository
git clone https://github.com/yourusername/spring-chatroom.git
cd spring-chatroom

3. Build the Project
Use Maven to build the project:
mvn clean install

3. Run the Application
After building, you can run the application:
mvn spring-boot:run
Alternatively, you can run the compiled .jar file (located in the target folder):
java -jar target/spring-chatroom-0.0.1-SNAPSHOT.jar

4. Access the Chatroom
Once the application is running, open your web browser and go to:
http://localhost:8080

5. Using the Chatroom
Enter your name and start chatting with other users in real-time.
Messages will appear instantly as you send them.
Technologies Used
Spring Boot: Backend framework
WebSocket: Real-time message transmission
Maven: Build automation tool
Contributing
Feel free to fork this repository, create a feature branch, and submit pull requests for improvements!

License
This project is licensed under the MIT License. See the LICENSE file for more details.
