# Node.js, Express and OpenAI Conversational AI Assistant

A simple and easy-to-use conversational AI assistant built using Node.js, Express, and OpenAI's text completion API.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You'll need to have Node.js and npm (Node Package Manager) installed on your machine. You can download and install them from the official website if you don't already have them.

### Installing

1. Clone the repository to your local machine

```
git clone https://github.com/Xekhai/nodejsAIAssistant.git
```

2. Navigate to the project directory

```
cd nodejsAIAssistant
```

3. Install the project dependencies

```
npm install
```

4. Create a `.env` file in the project root directory and add your OpenAI API key
```
OPENAI_API_KEY = your-openai-api-key
```
5. Start the development server

```
node index.js
```

The app will now be running at `http://localhost:3000`.
#
## Usage
To send a message to the AI assistant, you can make a POST request to the /converse endpoint with the message in the request body, like so:

```
$ curl -X POST -H "Content-Type: application/json" -d '{"message":"Hello, who are you?"}' http://localhost:3000/converse
```
The AI assistant will respond with a completed message, which will be returned in the response data.

## Customization
This codebase provides a basic conversational AI assistant that can be customized to suit your specific needs. You can adjust the conversation context prompt, change the temperature and parameters of the text completion API, or add new endpoints to handle different types of requests.

## Built With

- [Node.js](https://nodejs.org/) - A JavaScript runtime built on Chrome's V8 JavaScript engine
- [Express](https://expressjs.com/) - A fast, unopinionated, minimalist web framework for Node.js
- [OpenAI](https://openai.com/) - An artificial intelligence research laboratory consisting of the for-profit technological company OpenAI LP and its parent company, the non-profit OpenAI Inc
- [Body-Parser](https://www.npmjs.com/package/body-parser) - A body parsing middleware for Node.js
- [Dotenv](https://www.npmjs.com/package/dotenv) - A zero-dependency module that loads environment variables from a .env file

## Contributing

Contributions are welcome! If you have any ideas or suggestions, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

