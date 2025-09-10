# JavaFX Tic-Tac-Toe
A classic Tic-Tac-Toe game with a clean, modern GUI built using JavaFX. Play against an AI opponent and test your skills in this simple yet challenging game.

# Features
Player vs. AI: Challenge a smart AI opponent.

Interactive GUI: A user-friendly graphical interface for an engaging experience.

Start Choice: Decide whether the human player ('X') or the AI ('O') goes first.

Game Status: Clear messages indicating the current player, game win, or a draw.

# Getting Started
This project requires a JDK (Java Development Kit) and a configured JavaFX environment in your IDE. The recommended JDK version is 17 or higher.

# Prerequisites
A Java Development Kit (JDK) 17+ installed on your system.

The latest JavaFX SDK. You can download it from the official OpenJFX website.

# IntelliJ IDEA Setup
Open the Project: Open the TicTacToe project in IntelliJ IDEA.

Configure JDK: Go to File > Project Structure. Under Project Settings, ensure your project SDK is set to a JDK 17+ version.

Add JavaFX SDK as a Library:

In Project Structure, navigate to Libraries under Platform Settings.

Click the + icon and select Java.

Navigate to the lib directory of your downloaded JavaFX SDK and select all the JAR files. Click OK.

- The new library should now appear. Click `Apply` and `OK`.

Add VM Options: This is a crucial step for running JavaFX applications.

Go to Run > Edit Configurations....

In the VM options field, add the following line:

--module-path /path/to/your/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml

Note: Replace /path/to/your/javafx-sdk/lib with the actual path to the lib directory of your JavaFX SDK.

# Eclipse Setup
Install the e(fx)clipse Plugin:

Go to Help > Eclipse Marketplace....

Search for e(fx)clipse and click Install. Follow the prompts to complete the installation and restart Eclipse.

Configure JavaFX SDK:

Go to Window > Preferences.

In the search bar, type JavaFX and select the entry.

Set the JavaFX SDK path to the base directory of your downloaded JavaFX SDK (e.g., C:\path\to\javafx-sdk).

Import the Project:

Go to File > Import... > General > Existing Projects into Workspace.

Browse for your project directory and click Finish.

Add VM Arguments:

Right-click the TicTacToe.java file and go to Run As > Run Configurations....

Select the (x)= Arguments tab.

In the VM arguments text area, add the following:

--module-path "C:\path\to\your\javafx-sdk\lib" --add-modules javafx.controls,javafx.fxml,javafx.graphics

Note: Replace "C:\path\to\your\javafx-sdk\lib" with the absolute path to the lib directory of your SDK.

# How to Run
After completing the IDE-specific configuration, simply run the TicTacToe.java file from your IDE. A new window with the game board should appear.

# Contributing
Feel free to fork this repository, make changes, and submit a pull request. All contributions are welcome!
