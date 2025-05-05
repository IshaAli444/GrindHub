# GrindHub
GrindHub is a study group application that integrates the functionality of a social network friend recommendation system. The application employs graph theory concepts to represent and analyze user relationships, providing features such as friend recommendations, mutual connections, and real-time user posts. Designed with Gen Z in mind, the app has a sleek black-and-brown theme, quirky quotes, and dynamic animations, offering a unique and engaging experience for students to connect, learn, and share.

Features and Functionalities
Core Functionalities:

1.	Add Friends
Users can form friendships by connecting with other users.
2.	Delete Friends
Users can break existing friendships if desired.
3.	Display Mutual Friends
The system identifies and displays mutual friends between two users.
4.	Suggest Potential Friends
Based on shared connections, the app suggests friends-of-friends to users, fostering new relationships.
5.	User Posting System
Users can create posts that are stored and displayed in First-Come-First-Serve (FCFS) order, simulating a real-time activity feed.
Additional Features:

•	Login and Sign-Up System
A secure authentication system with persistent data storage.
•	Real-Time Post Limiting
Limits posts to 10 per user, ensuring the feed remains relevant and focused.
•	Persistent Storage
Data (users, credentials, friendships, and posts) is stored in a file and loaded at startup.




3. Data Structures Used
Linear Data Structures:
•	Queue:
Used in the posting system to maintain the order of posts (FCFS).
Non-Linear Data Structures:
•	Graph:
The core structure representing the social network, where: 
o	Nodes represent users.
o	Edges represent friendships.


4. Tools and Technologies Used
•	Programming Language: Java
•	Framework: JavaFX for UI development
•	Backend: File-based persistent storage (using Java serialization)
•	Build Tool: Maven
•	IDE: IntelliJ IDEA and Visual Studio Code
•	Version Control: Git

I used **Maven** in this project to manage dependencies, automate the build process, and maintain a standardized project structure. Maven helped streamline development by handling library integration, compiling code, and packaging the application efficiently. All configurations and dependencies were managed through the **`pom.xml`** file.

I initially aimed to use **JSON** for cleaner, structured, and future-proof data storage using libraries like **Gson**. While I managed to serialize basic data, handling complex relationships (like friendships) became challenging. Due to deadline pressure, I switched to simpler **object serialization**, which ensured reliable storage with less complexity.
