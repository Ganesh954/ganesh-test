RSD Application
## Code Local setup

## cloning the repository
1. In command prompt, navigate to the folder you want to clone and then type the below command by replacing the approprioate paramaters.
```
  git clone <git repository url> <project name>
```

## Installation of package dependencies using npm
1.To run the project, you need to install the necessary dependencies, including `dotenv` for managing environment variables.
Follow these steps to install:

1. Open the terminal.
2. Navigate to the root directory of the project.
3. Run the following command to install `npm i dotenv`
4.This will add dotenv to the node_modules folder and list it as a dependency in the package.json file

## Environment Setup

1. Before running the application, you need to set up the environment variables. This project uses the `dotenv` package to manage environment variables.

2. To get started, create a `.env` file in the root directory of the project.

3. To load the variables from .env file into process.env, making them accessible throughout the application, add the below two lines of code at the beginning of app.js file(Backend file).

const dotenv = require('dotenv')
dotenv.config('.env')

## Running the application

Run the below two commands in the terminal of root directory of the project

1. npm i : This command install all the packages that are listed as dependencies in the project’s package.json file.These packages are installed in the node_modules folder within the project directory.

2. npm start: This command will start the application.


Note: You will get an error if you dont have PostgreSQl installed in your machine.Raise a RITM for the PostgreSQL installation.








