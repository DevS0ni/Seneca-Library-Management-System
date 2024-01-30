# Library Management System

*Project Description:* Library Management System

This project involves the creation of a Library Management System that manages publications such as books. 
The system incorporates various classes, including Menu, MenuItem, Book, and Date, to provide a comprehensive solution for handling library-related operations. 
The project is organized into multiple files, each containing classes and functionalities for specific components.

*Menu and MenuItem Classes (Menu.cpp and Menu.h):*
The Menu class represents a menu system that allows users to interact with different options.
It includes functionalities for displaying a menu, getting user input, and adding menu items dynamically.
The MenuItem class represents individual items in the menu, with support for creating, displaying, and managing menu content.

*Book Class (Book.cpp and Book.h):*
The Book class is part of the Library Management System and represents a book publication.
It inherits from the Publication class and includes additional features such as managing author names.
The class supports functionalities like reading and writing book information, copying, setting attributes, and checking validity.

*Date Class (Date.cpp and Date.h):*
The Date class handles date-related operations, including validation, manipulation, and comparison.
It incorporates error handling and includes functions to calculate the number of days since a reference date (0001/01/01).
The class is designed to work seamlessly with the Library Management System to handle publication dates.

*Utility Functions and Modules:*
The project includes utility functions such as numberOfDaysInMonth for calculating the number of days in a given month.
The systemYear function in the Date class retrieves the current system year, considering a test mode with a predefined year.

*Project Organization:*
The project is well-organized, with each class in its own set of files, promoting modularity and maintainability.
Namespaces (sdds) are used to encapsulate related classes and avoid naming conflicts.

*Input and Output Handling:*
The project incorporates input and output stream operators (<< and >>) for seamless interaction with streams.
Input validation and error handling are implemented to ensure the correctness and reliability of user inputs.

*Testing and Debugging:*
The project includes a testing mode (sdds_test) for specific date-related functionalities, enhancing reliability and testability.
Proper error codes and error handling mechanisms are in place to facilitate debugging and user feedback.

*User Interaction:*
The Menu class provides an interactive menu system for users to navigate through various options, enhancing the user experience.
The system allows users to input information about books and manage library-related operations.

*Date Comparison and Arithmetic:*
The Date class overloads comparison operators (==, !=, >=, <=, <, >) and the subtraction operator (-) for date-related comparisons and calculations.
This Library Management System provides a solid foundation for managing book publications, handling dates, and offering an interactive menu system for users. 
The project demonstrates object-oriented programming principles, encapsulation, and modular design, making it suitable for a library or similar information management system.

# To run the Library Management System project, follow these steps:

> Set Up Your C++ Development Environment:
Make sure you have a C++ compiler installed on your system. You can use an integrated development environment (IDE) like Visual Studio, Code::Blocks, or any other C++ compiler.

> Download or Clone the Project:
Download the source code files for your project, or clone the repository if it's hosted on a version control platform like GitHub.

> Open the Project in Your C++ IDE:
Open the main project file, typically named main.cpp or another file specified as the entry point, in your C++ IDE.

> Build the Project:
Build the project to compile the source code. This process may involve clicking a "Build" or "Compile" button in your IDE.

> Run the Executable:
After successfully building the project, locate the generated executable file. The name of the executable file is usually the same as the project name or as specified in your IDE.
Run the executable by double-clicking on it or executing it from the command line.

> Interact with the Library Management System:
Follow the prompts and menu options displayed in the console or command line interface to interact with the Library Management System.
Use the provided functionalities such as adding books, navigating menus, and performing library-related operations.

> Enter Input as Needed:
Enter input as requested by the program. For example, when adding a book, follow the prompts to input book details.

> Explore Menu Options:
Utilize the menu options provided by the Menu class to navigate through different functionalities within the Library Management System.

> Review Output:
The program will display relevant information about books, dates, and other library-related operations.

> Exit the Program:
Follow the prompts to exit the program when you are done exploring and interacting with the Library Management System.

*-> NOTE: Keep in mind that the specific steps may vary based on the C++ IDE you are using.*
