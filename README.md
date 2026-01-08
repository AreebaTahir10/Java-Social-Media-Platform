# Java-Social-Media-Platform
A fully functional, enterprise-grade Social Media Application built with Java, Swing, and MongoDB. This project demonstrates advanced Object-Oriented Programming (OOP) principles, clean architecture, and cloud-native database integration.

## 🚀 Features

### Core Functionality
*   **User Authentication**: Secure Login and Signup system.
*   **User Profiles**: Customizable profiles with Bios, Profile Pictures (stored in cloud), and Stats.
*   **Social Feed**: Create posts, Like, and Comment on friends' activities.
*   **Follow System**: Connect with other users to see their updates.

### Advanced Engineering
*   **Recommendation Engine**: Smart user suggestions based on mutual connections.
*   **Real-Time Messaging**:
    *   Direct 1-on-1 Chat.
    *   **Group Chats**: Create groups, add members, edit details, and delete groups.
    *   Live updates without refreshing.
*   **Activity Feed**: Unified stream of all interactions (Likes, Follows, Comments).
*   **Notifications**: Real-time alerts for user interactions.
*   **Search**: Find users by username.

### Technical Highlights
*   **Custom Design System ("ModernUI")**: A centralized UI library built on Swing to provide a consistent, modern, clean look (Dark/Light themes support capable).
*   **Cloud Storage**:
    *   **MongoDB Atlas**: scalable NoSQL database for structured data.
    *   **GridFS**: Binary storage for handling large media files (images).
*   **Architecture**:
    *   **MVC (Model-View-Controller)**: Strict separation of concerns.
    *   **DAO (Data Access Object)**: Decoupled database operations.
    *   **Singleton Services**: Efficient resource management.

## 🛠️ Technology Stack

*   **Language**: Java (JDK 21+)
*   **GUI Framework**: Java Swing
*   **Database**: MongoDB Atlas (Cloud)
*   **Drivers**: MongoDB Java Driver
*   **Build Tool**: Custom / IDE-based

## 📂 Project Structure

```
src/
├── dao/          # Data Access Objects (Database Layer)
├── gui/          # Swing UI Components & Panels (ModernUI)
├── model/        # Data Models (POJOs)
├── service/      # Business Logic & Algorithms
└── Main.java     # Application Entry Point
```

## ⚙️ Setup & Installation

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/yourusername/social-media-java.git
    cd social-media-java
    ```

2.  **Configure Database**
    *   Open `src/dao/DBConnection.java`.
    *   Update the `MONGO_URI` with your MongoDB Atlas connection string.
    *   Ensure your IP is whitelisted in MongoDB Atlas.

3.  **Dependencies**
    *   Ensure the **MongoDB Java Driver** jars are added to your classpath.

4.  **Run the Application**
    *   Compile and run `src/Main.java`.

## 👨‍💻 Contributors

*   **[Maryam Manahil]**
*   **[Ayesha Altaf]**
*   **[Ifrah Imran]**
