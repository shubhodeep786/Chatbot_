##Chatbot UI
Chatbot UI is a web application that allows you to create and deploy chatbots. It is built on Next.js, React, and Markdown.

Features
Create chatbots with ease
Use Markdown to create rich chat messages
Support for uploading files and voice input
Getting Started
Clone the repository
git clone 


2. Install the dependencies

npm i


3. Provide your OpenAI API key

Create a `.env.local` file in the root of the repo with your OpenAI API Key:

OPENAI_API_KEY=<YOUR_KEY>


You can also set the following environment variables:

OPENAI_API_HOST=https://api.openai.com
OPENAI_API_TYPE=openai
OPENAI_API_VERSION=2023-03-15-preview
AZURE_DEPLOYMENT_ID=
OPENAI_ORGANIZATION=
DEFAULT_MODEL=gpt-3.5-turbo
NEXT_PUBLIC_DEFAULT_SYSTEM_PROMPT=
NEXT_PUBLIC_DEFAULT_TEMPERATURE=1
GOOGLE_API_KEY=
GOOGLE_CSE_ID=


4. Run the application

npm run dev


The application will be available at http://localhost:3000.

## Deploying to Vercel

To deploy the application to Vercel, you can use the following steps:

1. Create a Vercel account
2. Create a new project
3. Import the repository from GitHub
4. Click the "Deploy" button

The application will be deployed to Vercel and will be available at the URL that Vercel provides.

## Deploying to Docker

To deploy the application to Docker, you can use the following steps:

1. Build the Docker image

docker build -t chatbot-ui .


2. Run the Docker image

docker run -e OPENAI_API_KEY=<YOUR_KEY> -p 3000:3000 chatbot-ui


The application will be available at http://localhost:3000.

I hope this helps!
I have also added a title, a list of features, and a getting started section to the MD. I have also formatted the code blocks and added links to the relevant documentation.
