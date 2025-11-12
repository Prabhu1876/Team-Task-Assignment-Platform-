# Team-Task-Assignment-Platform-




# Team Task Assignment Platform

A Java-based mini-project that provides a platform for team leaders to create, assign, and track tasks for team members.

## 📜 Description

This project is a simple, command-line or GUI-based (you can specify which) application built in Java. It solves the basic problem of task management within a small team. It allows for two types of users: **Admins (or Team Leaders)** and **Team Members**.

* **Admins** can register new members, create new tasks, assign tasks to members, and view the status of all tasks.
* **Team Members** can view their assigned tasks, update the status of a task (e.g., "Pending", "In Progress", "Completed"), and view task details.

## ✨ Features

* **User Authentication:** Secure login for Admins and Team Members.
* **User Roles:** Distinct permissions for Admins and regular Members.
* **Task Creation:** Admins can create tasks with a title, description, and due date.
* **Task Assignment:** Admins can assign tasks to one or more team members.
* **Task Tracking:** All users can view tasks, and members can update the status of their own tasks.
* **Dashboard View:**
    * **Admin Dashboard:** View all tasks, filter by user, or filter by status.
    * **Member Dashboard:** View only tasks assigned to them.

## 🛠️ Technologies Used

* **Core Language:** Java
* **Database:** (e.g., MySQL, PostgreSQL, or "In-memory data structures" if you didn't use a DB)
* **Database Connectivity:** JDBC (if a DB was used)
* **GUI (Optional):** JavaFX or Swing (if you built a GUI)
* **Build Tool (Optional):** Maven or Gradle (if used)

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing.

### Prerequisites

What things you need to install the software:

* Java Development Kit (JDK) 11 or higher
* (e.g., MySQL Server)
* (e.g., Apache Maven)

### 💾 Installation

A step-by-step guide on how to get the development environment running:

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/your-project-repo.git](https://github.com/your-username/your-project-repo.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd your-project-repo
    ```
3.  **Database Setup (if applicable):**
    * Import the `database.sql` file into your MySQL instance.
    * Update the database credentials in `src/main/java/com/yourproject/utils/DBConfig.java` (or your config file).
4.  **Build the project (if using Maven/Gradle):**
    ```sh
    mvn clean install
    ```
5.  **Run the application:**
    * **If it's a command-line app:**
        ```sh
        java -jar target/YourProjectName-1.0.jar
        ```
    * **If running from an IDE:**
        Find the `Main.java` file and run it.

## Usage

Here are the default login credentials for testing:

**Admin:**
* **Username:** `admin`
* **Password:** `admin123`

**Team Member:**
* **Username:** `member`
* **Password:** `member123`

Once logged in, follow the on-screen prompts to navigate the application.

* **As Admin:**
    1.  Select "Create Task" to add a new task.
    2.  Select "Assign Task" to assign it to a registered member.
    3.  Select "View All Tasks" to see the status of everything.
* **As Member:**
    1.  Select "View My Tasks" to see your queue.
    2.  Select a task to update its status to "In Progress" or "Completed".

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 👥 Contributors

* **[Your Name]** - *Project Lead* - [your-github-username](https://github.com/your-github-username)
* (Add other team members here if you have them)
