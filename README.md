# C# Class Registration Application

This repository contains the source code and documentation for a C# application designed to register students for courses.

## Application Summary and User Needs

This application was developed to simulate a student registration system. The requirements included validating user selections, enforcing business rules (no duplicate registrations, maximum credit hours), and providing clear feedback to the user. The application addresses the need for a simple and efficient way for students to register for courses while adhering to academic policies.

## Development Highlights

I particularly excelled at implementing the business logic and ensuring the application adhered to all requirements. I was able to successfully take existing code, and expand on it to provide a fully functional application. The validation and error handling were also implemented effectively, providing a user-friendly experience.

## Console vs. WPF Application Design

The Console application provided a basic, text-based interface, while the WPF application offered a more interactive and visual experience.

* **Console:**
    * Simple input/output, suitable for basic functionality.
    * Limited user interaction.
* **WPF:**
    * Graphical user interface with combo boxes, list boxes, and text boxes.
    * Enhanced user experience with visual feedback and clear layout.
    * The WPF application used a combo box to select courses, a list box to display registered courses, and a text box to show total credit hours. This kept the UI focused and easy to use. The design was successful because it provided clear visual feedback and made the registration process intuitive.

## Debugging and Coding Approach

I used a systematic approach to debugging and coding. I broke down the requirements into smaller tasks, implemented them incrementally, and tested each part thoroughly. I used debugging tools in Visual Studio to step through the code and identify issues. I also used console output and message boxes to track variable values and program flow. In the future, I will continue to use these techniques and also incorporate unit testing to ensure code quality.

## Innovation and Challenges

One challenge was ensuring the WPF application updated the UI correctly after each registration. I had to be innovative in how I forced the listbox to refresh its contents. I overcame this by setting the listbox's item source to null, and then resetting it to the registered courses list. This forced the listbox to update.

In the console application, I had to be innovative in my use of loops and conditional statements to ensure that the user input was properly validated.

The step by step process was:

1.  Analyze the requirements.
2.  Design the UI and logic.
3.  Implement the core functionality.
4.  Add validation and error handling.
5.  Test thoroughly.
6.  Refine the code and UI.
7.  Document the process.
