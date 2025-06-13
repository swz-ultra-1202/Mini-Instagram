# Mini Instagram (Console-Based)

This is a C++ project that simulates a simplified version of Instagram. It includes core functionalities such as user registration, login, sending messages, managing posts, and handling friend requests. The program runs in a terminal environment and uses Windows-specific libraries for UI enhancements.

## Features

### User Management
- Register with username, password, city, and security question/answer.
- Login and logout functionality.
- Search for users by name.

### Messaging System
- Send direct messages to users.
- View messages in a stack.
- Reply to messages with threaded replies.

### Friend Requests
- Send and accept friend requests.
- Manage followers and following lists.
- View request status notifications.

### Posts and News Feed
- Create new posts with automatic timestamps.
- View your posts.
- View posts from followed users in a personalized news feed.

### Notifications and Activity
- View list of followers and following users.
- View friend request notifications.
- View last login time.

## Data Structures Used

- Linked Lists: for posts, replies, followers, following, and notifications.
- Stack: for storing user messages.
- Queue: for processing friend requests.
- Binary Search Tree (BST): for storing and searching users efficiently.

---

## Project Setup and Execution

### Visual Studio 2022 (Empty Project)

1. Open Visual Studio 2022.
2. Go to **File > New > Project**.
3. Select **Empty Project (C++)**, not "Console App".
4. Set the project name (e.g., `MiniInstagram`) and click **Create**.
5. In **Solution Explorer**, right-click **Source Files > Add > New Item**.
6. Select **C++ File (.cpp)** and name it (e.g., `main.cpp`).
7. Paste the full source code into this file.
8. Press **Ctrl + F5** to build and run the project.

### Dev-C++ (Empty Project)

1. Open Dev-C++.
2. Go to **File > New > Project**.
3. Select **Empty Project** and choose **C++ Project**.
4. Name your project and save it.
5. When prompted, create a new source file.
6. Paste the full source code into the new `.cpp` file.
7. Save the file.
8. Go to **Execute > Compile and Run** or press **F11**.

---

## Requirements

- Windows OS (uses `<Windows.h>` for console UI effects)
- C++ Compiler (Visual Studio, Dev-C++, or any standard-compliant compiler)
- C++11 or later

---

## Notes

- The project uses Windows-specific functions such as `Sleep()` and colored console output. It will not run on Linux or macOS without modification.
- For cross-platform compatibility, remove or replace `Windows.h` and related function calls.

---

## Author

Muhammad Shah Nawaz
Email : shahnawaz.swz1202@gmail.com


## License

This project was created for academic use. It does not rely on any third-party libraries or frameworks.
