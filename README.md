## Header parser microservice (freeCodeCamp Back End and APIs)

**Project Overview:**

This project, completed as part of the Back End Development and APIs course by freeCodeCamp, implements a simple "Who Am I" API. It utilizes Node.js and Express.js to analyze the incoming request and return information about the user's IP address, preferred language, and browser/operating system.

**Key Features:**

- Retrieves the user's IP address from the request headers.
- Detects the user's preferred language based on the "Accept-Language" header.
- Identifies the user's browser and operating system based on the "User-Agent" header.
- Returns a JSON object containing the extracted information.

**Getting Started:**

1. **Prerequisites:** Node.js and npm (or yarn) installed on your system.
2. **Clone this repository:** `git clone git@github.com:karimAoulallay/fcc-header-parser-microservice.git`
3. **Install dependencies:** `npm install` or `yarn install`
4. **Run the project:** `npm start` or `yarn start`
5. **Test the API:** Access the API endpoint at `http://localhost:3000/api/whoami` using a browser or API testing tool.

**Response Example:**

```json
{
  "ipaddress": "127.0.0.1",
  "language": "en-US",
  "software": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/110.0.0.0 Safari/537.36"
}
```
