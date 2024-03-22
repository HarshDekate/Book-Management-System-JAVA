# Book Management System - Java

Welcome to Libzazy Book Management System! This project is a Java-based system designed to efficiently manage books in a library setting. It provides a comprehensive set of features for both users and administrators, ensuring smooth operation and organization of library resources.

## Features

### User Interface

The system offers a console-based user interface, providing a simple yet effective means of interaction for users and administrators.

### User Functions

- **Login:** Users can log in securely to access their accounts and perform various actions.
- **Search Books:** Users can search for books by title, author, genre, or any other relevant criteria.
- **View Book Details:** Detailed information about each book, including availability status and location, can be viewed.
- **Check Out/Return Books:** Users can check out books they wish to borrow and return them when they are done.

### Administrative Functions

- **Admin Login:** Administrators have privileged access to the system through secure login.
- **Add New Books:** Administrators can add new books to the library catalog, including details such as title, author, genre, and publication date.
- **Manage Users:** Administrators can add new users to the system, modify user information, and handle user-related tasks.
- **View Issued Books History:** The system maintains a record of all issued books, allowing administrators to track borrowing history.
- **View All Books in Library:** Administrators can view a comprehensive list of all books available in the library, along with their details and availability status.

### Logging Out

Users and administrators can securely log out of their accounts to ensure data privacy and system security.

## Getting Started

To run the Book Management System on your local machine, follow these steps:

1. Clone the repository:

   ```
   git clone https://github.com/your-username/Book-Management-System-JAVA.git
   ```

2. Navigate to the project directory:

   ```
   cd Book-Management-System-JAVA
   ```

3. Compile the Java files:

   ```
   javac *.java
   ```

4. Run the main Java file:

   ```
   java Main
   ```

5. Follow the prompts on the console interface to interact with the system.

## Class Diagram

The class diagram of the project is provided in the `blank_diagram.jpeg` file. You can open this file using Star UML or any compatible tool to visualize the structure of the system.

![Class Diagram](Book-Management-System-JAVA/Blankdiagram.jpeg)

Note: After refactoring, a new class named "HoldRequestOperations" has been added to remove bidirectional dependencies between `HoldRequest` and `Book` classes. For more details, refer to the [Refactoring Details](#refactoring-details) section below.

## Database Schema

The database schema of the project is provided in the `database_schema.sql` file. You can use this schema to set up the database for the system.

## Refactoring Details

After refactoring, the new `HoldRequestOperations` class has been added to the project structure. This class sits between the `HoldRequest` and `Book` classes, eliminating the bidirectional dependency between them. This enhances the modularity and maintainability of the system.

## Contributions

Contributions to this project are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request on GitHub.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to reach out if you have any questions or need further assistance. Happy managing your books! 📚🖥️
