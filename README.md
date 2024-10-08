# AWS Node.js TypeScript Serverless Template

This is a Serverless Framework template for creating AWS Lambda functions and API's using Node.js and TypeScript. This template provides a basic setup to get started quickly with TypeScript development in AWS.

## Features

- **TypeScript:** Support for TypeScript out-of-the-box.
- **AWS Lambda:** Deployment configuration for AWS Lambda functions.
- **Pre-configured:** Includes sample handler functions and serverless.yml setup.

## Getting Started

To create a new project using this template, follow these steps:

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or above)

- [Serverless Framework](https://www.serverless.com/) (v2 or above)

  Run the following command to install serverless framework globally:

  ```bash
  npm i serverless -g
  ````

- [AWS CLI](https://aws.amazon.com/cli/) (configured with your AWS credentials)

### Installation

Run the following command to create a new project using this template:

```bash
sls create --template-url https://github.com/JvFern4ndes/aws_nodejs_typescript --path <your-project-name>
````

## Deploying the Project

After creating your project, navigate to the project directory and deploy it to AWS:

```bash
cd <your-project-name>
npm install
serverless deploy
````

## Project Structure

* **handler.ts:** Your Lambda function code.
* **serverless.yml:** The Serverless Framework configuration file.
* **tsconfig.json:** TypeScript configuration.

## Customization

You can customize this template to fit your project needs by modifying the `serverless.yml`, adding additional resources, or changing the function handlers.

## Contributing

Contributions are welcome! If you find a bug or have a feature request, please open an issue or submit a pull request.
