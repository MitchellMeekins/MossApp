MossApp is a graphical user interface (GUI) designed for Windows systems that streamlines the use of MOSS (Measure of Software Similarity). MOSS is an automated tool widely used to detect similarities in software code, primarily to identify instances of plagiarism in programming courses. By providing an accessible GUI, MossApp simplifies the process of submitting programs to MOSS, eliminating the need for command-line interactions and making it more convenient for educators and developers to analyze code similarity.
 
 The current version was created using C# 4.7.2 and includes the Visual Studio 2017 solution folder. 

This is version 2.0 and includes a better UI, error handling, and various quality of life fixes (saving id and options to user settings, information on requesting a MOSS ID, etc.)

I have published the solution to create the installer. It is located in \MossApp\MossApp\Publish

If you find any errors, please let me know: smay1@nwacc.edu

Thank you. 

# Installation Guide
### **Prerequisites**
A registered Moss account. Check out the **_Registering for Moss_** section [here](https://theory.stanford.edu/~aiken/moss/)
### **Windows Installation Guide**
1. Install the project zip MossApp.zip
2. Extract the MossApp.zip project
3. Navigate to MossApp/Publish/Setup.zip
4. Extract the contents of Setup.zip
5. Locate the extracted setup.exe on your machine
6. Double-click to run the setup.exe file inside the extracted folder
7. Once the installation is complete, run MossApp
  
**Usage Guide**  
1. Enter your User Id in the UserId field. Please see [here](https://theory.stanford.edu/~aiken/moss/) for additional information
2. Choose source files (files you want to compare)
3. Select a programming language
4. Change any additional settings according to your needs
5. Click the _Send Request_ button
6. Once the request has finished, a link to your results will be above the _Send Request_ button
