# <h1 align="center">Logo-Maker</h1>
Week-10 Challenge
##  Description 
This app empowers freelance web developers to create custom logos without hiring a graphic designer. It uses inquirer to prompt users for logo preferences, such as up to three characters of text, text color, and shape (triangle, square, or circle) with a corresponding color. After answering the prompts, the app generates an SVG file with the user's selections. I also implemented unit testing for the first time, with a test suite consisting of three tests to ensure accurate shapes and colors. This app showcases the potential of back-end developers and the importance of unit testing, even for small projects. I added minor error handling for the first prompt, limiting text input to three characters. Future improvements could include additional error handling for SVG colors, more unit tests, and expanded font and polygon options. All in all, creating this app was a valuable learning experience that further developed my developer mindset.
## Table of Contents

*  [Description](#Description)
          <a name="Screenshots"></a>  

*  [Screenshots](#Screenshots)
          <a name="Screenshots"></a>    
 
##  Live Screen Recording of Application Functionality 
https://drive.google.com/file/d/1833SYkvuG8B2m24mdbQBHrW7q9xDsov1/view

## Screenshots 

logo generation

<img width="1470" alt="image" src="https://user-images.githubusercontent.com/121422214/236074863-a763482d-1b4a-462d-93e5-18d5bf6e9aa8.png">
<img width="1026" alt="Screenshot 2023-05-03 at 4 46 41 PM" src="https://user-images.githubusercontent.com/121422214/236075291-6dc2fde8-d3c5-415d-84cd-b88da7c48f05.png">
<img width="817" alt="Screenshot 2023-05-03 at 4 45 04 PM" src="https://user-images.githubusercontent.com/121422214/236075333-7bd33531-e086-4c32-8765-279e1e21cee8.png">
Examples of Generated Logos
<img width="323" alt="Screenshot 2023-05-03 at 5 31 20 PM" src="https://user-images.githubusercontent.com/121422214/236079419-ba090c98-022d-4f75-b76e-677a9c3126f2.png">
<img width="323" alt="Screenshot 2023-05-03 at 5 33 44 PM" src="https://user-images.githubusercontent.com/121422214/236079587-1c8c93db-abee-43b7-b860-fe5b61e12ea1.png">
<img width="323" alt="Screenshot 2023-05-03 at 5 36 09 PM" src="https://user-images.githubusercontent.com/121422214/236079906-4106014d-85ed-4008-8f1a-abd9ff592793.png">

## Technologies Used

This project utilizes Node.js v16, inquirer v8.2.4 (node package manager), and file system module (node package manager), as well as jest v29.5.0 (node package manager) for conducting unit testing.

## Installation

1. Clone the repo: git clone git@github.com:Slfdspln/logo-maker.git
2. To access, utilize VS Code. Installation is necessary if not currently installed.
3. To install node.js v16 using the terminal, refer to the documentation for the appropriate command. For instance, if you have homebrew, you can use the command 'brew install node@16'.
4. After installing node.js v16, use the command "npm init -y" in the terminal to create a package.json file for storing project files.
5. 
Using the terminal, run "npm i" to install the application's dependencies. For inquirer and jest, developers can install them directly from the command line using "npm i inquirer@8.2.4" for version 8.2.4 of inquirer and "npm i jest" for the latest version of jest.
6. Type "node index.js" in the terminal to run the application.

## Usage Information

To run the application, navigate to its directory using the command line, install dependencies (npm i), and run the command "node index.js". Answer the questions that follow and once done, a message will appear confirming the logo generation. Check the newly generated SVG file for your new logo.

For unit testing, refer to the Test Instructions section.

## Test Instructions

To perform unit testing, execute the command "npm run test" in the terminal. Currently, there is a single test suite containing three tests. This suite verifies that the render() method generates the correct string for the specified shape color in the associated SVG file.

<img width="797" alt="Screenshot 2023-05-03 at 5 59 53 PM" src="https://user-images.githubusercontent.com/121422214/236083446-1826fb1d-4699-4e3b-8a0f-be6412ee4d30.png">

## License

NOTICE: This application is covered under the MIT License

## Questions

Need more information? You can contact me through my GitHub or email. Links provided below.


