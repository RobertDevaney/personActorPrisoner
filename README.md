# personActorPrisoner

Robert Devaney
202320 Java Programming COP-2800C-22542

This program is a record application for managing information about people, actors, and prisoners. The program is implemented in Java.

    Add a Person: Users can input details about a person, including their name, height, and weight.
    Add an Actor: In addition to the basic person details, users can input an actor's main genre and the total number of movies they have made.
    Add a Prisoner: Users can input a prisoner's details, including the type of crime, years sentenced, and years remaining.
    Display All Records: Displays a list of all records (people, actors, and prisoners) that have been entered into the system.
    Summary: Provides a summary of the total number of people, actors, and prisoners, along with the most experienced actor and the prisoner with the longest time served.

Usage

    When you run the application, a main menu will be displayed, allowing you to choose from the following options:
        1: Add a Person
        2: Add an Actor
        3: Add a Prisoner
        4: Display all records to screen
        5: View a summary of the records
        6: Quit the application

    Input the relevant information as prompted by the dialog boxes for each option.
    The application will validate the input to ensure that it meets the expected criteria (height, weight, crime type, etc..).
    Use the summary option to view an overview of the records and identify key details such as the most experienced actor and the prisoner with the longest sentence.

Requirements

    Java Development Kit (JDK) 8 or higher

Classes

    Main: Handles the main menu and controls the flow of the application.
    Person: Represents a basic person with attributes such as name, height, and weight.
    Actor: Extends the Person class and includes additional attributes for an actor's main genre and total movies made.
    Prisoner: Extends the Person class and includes additional attributes for a prisoner's crime type, years sentenced, and years remaining.
    Name: A helper class that encapsulates a person's first name, middle initial, and last name.

Concepts

    Encapsulation: Keeping data safe within classes using private variables and public methods.
    Inheritance: Creating new classes (Actor, Prisoner) that share common traits from a base class (Person).
    Control Structures: Using loops and switch-case to handle user choices and guide the program.
    Exception Handling: Managing errors by checking for bad input and responding appropriately.
