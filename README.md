# Personal-Diary-Management

**Overview**
This is a simple console-based Personal Diary Management System implemented in C++. The project allows users to add, view, edit, and delete diary entries. It also provides the functionality to change the login password for added security.

**Features**
Login System: Users are required to enter a password to access the diary management system, providing a basic level of security.

Add Record: Users can add diary entries with details such as date, time, meeting person, meeting place, duration, and notes.

View Record: Users can view diary entries either for the entire day or for a specific time.

Edit Record: Users can edit existing diary entries, modifying details like time, meeting person, meeting place, duration, or notes.

Delete Record: Users have the option to delete either the entire diary for a specific day or a specific entry based on the time.

Change Password: The system allows users to change the login password for enhanced security.

**Project Structure**
main.cpp: Contains the main menu, user interface, and the switch case for various options.

functions.cpp: Implements the core functions such as adding, viewing, editing, and deleting diary entries.

password.cpp: Manages the login and password-related functions.

**Setup Instructions**
Prerequisites:
C++ compiler (e.g., GCC)
Code editor (e.g., Visual Studio Code, Sublime Text)
Terminal or Command Prompt
Steps:
Clone the Repository:

bash
Copy code
git clone https://github.com/your-username/diary-management.git
cd diary-management
Compile the Code:

bash
Copy code
g++ main.cpp functions.cpp password.cpp -o diary.exe
Run the Application:

bash
Copy code
diary.exe
Follow the On-Screen Instructions:

Enter the password to access the diary management system.
Use the main menu to add, view, edit, or delete diary entries.
Usage
Adding a Record: Choose option 1 from the main menu, enter the date, and follow the prompts to add a new diary entry.

Viewing Records: Option 2 allows you to view either the entire day's records or a specific time's entry.

Editing Records: Select option 3, enter the date and time, and follow the prompts to modify the existing diary entry.

Deleting Records: Choose option 4, and select whether you want to delete the entire day's records or a specific entry based on time.

Changing Password: Option 5 lets you change the login password for added security.

Exiting the Application: Select option 6 to exit the diary management system.

**Contribution Guidelines**
Contributions to enhance features, fix bugs, or improve the code are welcome. Please fork the repository, create a new branch for your changes, and submit a pull request.
