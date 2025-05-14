
# Gemini AI API Practice

This project demonstrates how to integrate the Gemini AI API with a Node.js backend. It allows you to interact with Gemini API using your own API key.

## Prerequisites

- Node.js version 18 or higher

## Setup Instructions

### 1. Clone the Repository

Start by cloning the repository to your local machine:

```bash
git clone https://github.com/jdelacruz23/gemini-AI-API-Practice.git
cd gemini-AI-API-Practice or the path where the repo was created
````

### 2. Initialize the Project

Initialize the project by running:

```bash
npm init -y
```

This will create a `package.json` file with default settings.

### 3. Install Required Packages

Install the required dependencies:

```bash
npm install express
npm install dotenv --save
npm install @google/genai
```

### 4. Create the `.env` File

In the root directory of the project, create a `.env` file. Add your Gemini API key to this file:

```
GEMINI_API_KEY={your GEMINI API key}
```

Replace `{your GEMINI API key}` with your actual API key.

### 5. Run the Application

Once everything is set up, open a terminal, navigate to the project folder, and start the server with:

```bash
node app.js
or
nodemon app.js (if you have nodemon installed, if not you can install it by npm install nodemon)
```

Then go to http://localhost:3000

The app should now be running, and you can start interacting with the Gemini AI API.

