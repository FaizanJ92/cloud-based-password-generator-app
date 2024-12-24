# Cloud-Based Password Generator App

## Overview
This is a cloud-based password generator application that allows users to generate strong, customizable passwords based on various criteria. The application leverages AWS services such as Lambda, API Gateway, DynamoDB, AWS Amplify for hosting, and the front-end is built using HTML, CSS, and JavaScript. It is designed to provide a simple and secure way for users to generate passwords without storing any sensitive information.

## Features
- **Customizable Password Generation**: Users can specify the length of the password and whether to include uppercase letters, numbers, and special symbols.
- **Secure**: The application ensures that the generated passwords are strong and follow industry best practices for password security.
- **Cloud Integration**: The app utilizes AWS Lambda for processing, API Gateway for handling requests, DynamoDB to store and retrieve password generation requests, and AWS Amplify for hosting the web application.

## Technologies Used
- **AWS Lambda**: To run the logic for generating passwords.
- **AWS API Gateway**: To expose the Lambda function as a RESTful API.
- **AWS DynamoDB**: To store password generation data and requests.
- **AWS Amplify**: To host the front-end of the application on the cloud.
- **JavaScript**: For the front-end logic to interact with the API.
- **HTML/CSS**: For designing the front-end of the application.

## How It Works
1. **User Input**: The user specifies the desired password length and selects options for including uppercase letters, numbers, and symbols.
2. **API Request**: The front-end sends a POST request to an AWS API Gateway endpoint with the user's input.
3. **Password Generation**: AWS Lambda processes the request and generates a secure password based on the provided criteria.
4. **Response**: The generated password is returned to the front-end and displayed to the user.

## Installation
To run the project locally, follow these steps:

### 1. Clone the repository
```bash
git clone https://github.com/FaizanJ92/cloud-based-password-generator-app.git
cd cloud-based-password-generator-app
