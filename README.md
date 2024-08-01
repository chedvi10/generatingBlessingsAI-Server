# Blessing Generator AI Server

This project is a Node.js server that generates blessings using OpenAI's GPT-3.5 model.

## Features

- Express.js server setup
- Integration with OpenAI API
- CORS enabled
- Environment variable configuration with dotenv
- Generates 3 blessings based on user input

## Installation

1. Clone the repository
2. Run `npm install` to install dependencies
3. Create a `.env` file in the root directory and add your OpenAI API key:



OPENAI_API_KEY=your_api_key_here PORT=3000


## Usage

1. Start the server with `node app.js`
2. Send a POST request to `/prompts` with a JSON body containing a `prompt` field
3. Receive 3 AI-generated blessings in JSON format

## API Endpoint

- POST `/prompts`
- Request body: `{ "prompt": "Your blessing request here" }`
- Response: JSON object with 3 blessings

