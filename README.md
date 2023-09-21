# Fastify Finance Manager

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Typescript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)

## Project Description

This money management API is a RESTful web service developed for managing and tracking financial transactions. It is designed using modern web technologies and provides the ability to perform various money management tasks.

## Features

Create a New Transaction: Users can create new financial transactions, specifying whether it's a credit (income) or debit (expense).

Get Account Summary: Retrieve the user's account summary, including the total balance.

List All Transactions: View a list of all transactions associated with the user's account.

View a Single Transaction: Access details of a specific transaction by providing its unique identifier.

User Authentication: Users can authenticate themselves in requests to ensure data privacy.

User-Specific Transactions: Users can only view transactions associated with their account.

## Technologies Used

Fastify: A fast and low-overhead web framework for Node.js.

Knex.js: A SQL query builder for Node.js.

TypeScript: A statically typed superset of JavaScript.

Vitest: A testing framework for JavaScript and TypeScript.

## Getting Started

### Prerequisites
- Node.js

### Installation 

1. Clone this GitHub repository to your local machine using the following command:

```
git clone https://github.com/Feelpe/fastify.finance.manager.git
```

2. Enter the project directory:

```
cd fastify-finance-manager
```

3. Install project dependencies using npm:

```
npm install
```

4. Configure your database connection details in the project's configuration file.

5. Start the API server:

```
npm run dev
```

6. Run tests to ensure the API functions correctly:

```
npm run test
```

🚧 Frontend in development 🚧

License
This project is licensed under the MIT License - see the LICENSE file for details.
