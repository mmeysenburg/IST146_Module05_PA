# IST146_Module05_PA

Now that you have gotten your hands on some Java file processing and streams with the Module 5 Hands-On Activity (HOA 5), it is time to put your skills to the test in this module's Programming Assignment (PA 5). In this PA, you will access some JSON data about wine from the Web, and use streams to perform some statistics on the dataset. 

## Instructions

1. Log on to your replit account. 
2. Click the "+ New repl" button to create a new repl. 
3. Click on the "Import from GitHub" tab. 
4. Type or paste the following URL into the "Paste any repository URL" text field: `github.com/mmeysenburg/IST146_Module05_PA`
5. Click on the "Import from github" button.
6. Click the "Done" button in the ".replit" dialog that appears.
7. THIS IS DIFFERENT: in the terminal area, execute this command: `mv replit .replit`. Executing this will set the classpath to allow the program to read a JSON file.
8. Select the `Main.java` file. Search for the keyword "TODO", and write the specified code.
9. At any time you can run the code from the user's perspective, or, from a developer's point of view, execute the unit tests that have been provided.
  * To run the code, click the "Run" button.
  * To execute the unit tests (if any), enter the following command in the "Console" tab: `bash test.sh`
10. Once you have completed the code correctly, the unit tests (if any) should pass, and running the code should produce results that make sense.
11. When you are finished, submit your `Main.java` file via the Canvas assignment.

## Files in the repository

* `Main.java`: Main program to run the code from a user's perspective. This file's `main()` method is invoked when you click the "Run" button.
* `wine.json`: Wine JSON file, for reference; your program should access it through the specified URL.
* `README.md`: This README file.
* `LICENSE`: GNU General Public License v3.0 for these materials.
* `jars`: Directory containing the libraries required to read JSON files.
* `replit`: File with code to enable the Run button in this project.
