# Request Header Parser Microservice (Express WhoAmI API)

This Node.js project utilizes the Express.js framework to create a simple API endpoint (`/api/whoami`) that provides information about the user's IP address, preferred language, and software. This API is designed to meet the requirements set by FCC (FreeCodeCamp) for a WhoAmI microservice.

## Features

- **IP Address Retrieval:** The API returns the user's IP address in the `ipaddress` key.
- **Language Information:** The preferred language of the user is included in the `language` key.
- **Software Details:** The user's software information is provided in the `software` key.

## Usage

### API Endpoint

- `/api/whoami`: Returns a JSON object with IP address, language, and software information.

### Example Response

```json
{
  "ipaddress": "127.0.0.1",
  "language": "en-US,en;q=0.9",
  "software": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/91.0.4472.124 Safari/537.36"
}
```

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/express-whoami-api.git
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file in the project root and set any necessary environment variables.

4. Start the server:

   ```bash
   npm start
   ```

   The API will be accessible at `http://localhost:3000/api/whoami`.

## Environment Variables

- **PORT:** Specifies the port on which the server will run. Default is `3000`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
