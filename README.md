# AI Recipe Generator App with AWS Bedrock

Open-source web application for generating personalized recipes based on user-provided ingredients.

# ✍️ Author(s) Details

- Colm Coffey MSc  
  - [LinkedIn](http://linkedin.com/in/colm-coffey/)  
  - [View Portfolio](https://drive.google.com/file/d/1JEqqHS_o56ehmzYib8gg85UB9U89VczC/view?pli=1)  

- AWS Solutions Architect

# Table of Contents

1. [Introduction 📖](#introduction-)
2. [Architecture Diagram 🖥️](#architecture-diagram-)
3. [Features ✨](#features-)
4. [Installation 🛠️](#installation-)
5. [Usage 🚀](#usage-)
6. [Contributing 🤝](#contributing-)
7. [License 📜](#license-)

## Introduction 📖

The AI Recipe Generator is a web application that lets users enter a list of ingredients to generate delicious, AI-powered recipes. It leverages AWS Amplify for seamless deployment and hosting, integrating various AWS services to create a scalable and responsive solution.

This project is developed via the [AWS Build a Serverless App Tutorial](https://aws.amazon.com/getting-started/hands-on/build-serverless-web-app-lambda-amplify-bedrock-cognito-gen-ai/) and extends its concepts to a practical AI-driven recipe application.

## Architecture Diagram 🖥️

![Architecture Diagram](![image](https://github.com/user-attachments/assets/b1293c0b-2012-4c50-b144-e14a8e6df0c9)
)
![image](https://github.com/user-attachments/assets/a20d8faf-c6d3-430f-a4c8-bc6b207e4ac3)


- **Users** interact with the app hosted on AWS Amplify.
- **AWS Amplify** handles the CI/CD workflow and frontend deployment.
- **Amazon Cognito** provides secure user authentication.
- **AWS AppSync** allows for real-time data queries using GraphQL.
- **AWS Lambda** processes backend logic, interfacing with Amazon Bedrock.
- **Amazon Bedrock** powers the AI recipe generation.

## Features ✨

- **Automated Deployment**: Continuous integration and deployment using AWS Amplify.
- **Secure User Authentication**: Managed by Amazon Cognito.
- **Scalable AI Backend**: Serverless processing via AWS Lambda and Amazon Bedrock.
- **Real-time Data Access**: Efficient queries with AWS AppSync and GraphQL.
- **Global Hosting**: Delivered on AWS's Content Delivery Network (CDN) for fast, global access.

## Installation 🛠️

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/ai-recipe-generator.git
   ```
2. Open the project in your preferred code editor.

3. Follow the steps to connect the repository to [AWS Amplify](https://console.aws.amazon.com/amplify/home) for automated deployment.

## Usage 🚀

1. Access the web app via the provided amplifyapp.com domain.

2. Enter a list of ingredients to generate a variety of recipe suggestions.

3. Browse through AI-generated recipes tailored to the ingredients provided.

4. Save or share your favorite recipes..
