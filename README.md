# Environment Variables

A simple Node.js project demonstrating how to use **environment variables** and `.env` files to store configuration values separately from the application code.

## Features

* Using `.env` files
* Storing configuration values as environment variables
* Accessing environment variables in Node.js
* Keeping sensitive configuration outside source code
* Using environment-specific settings

## Tech Stack

* **Node.js**
* **JavaScript**
* **dotenv**

## How It Works

Environment variables allow configuration values to be stored outside the main source code.

The project demonstrates how to:

1. Create a `.env` file.
2. Define configuration values inside it.
3. Load the variables into the Node.js application.
4. Access them using `process.env`.

## How to Run

1. Clone the repository.
2. Navigate to the project directory.
3. Install the dependencies:

```bash
npm install
```

4. Create a `.env` file and add the required environment variables.
5. Start the application:

```bash
node index.js
```

## Example

```env
PORT=3000
```

The variable can then be accessed in Node.js using:

```javascript
process.env.PORT
```

> **Note:** Do not commit sensitive `.env` values such as passwords, API keys, or database credentials to GitHub. Add `.env` to `.gitignore`.

## What I Learned

* Environment variables
* `.env` files
* Using the `dotenv` package
* `process.env`
* Separating configuration from application code

