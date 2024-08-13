# Next.js Gemini Voice Chat

This is a simple Next.js application that allows users to voice chat with the Google Gemeni.

## Getting Started

1. Clone the repository.
2. Install the dependencies with `npm install`.
3. Register your Google Gemini API key and add it to `.env.local` i.e. API_KEY=<api_key_here>.
4. Run the development server with `npm run dev`.
5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## API Route

The API route is located at `pages/api/chat.js`. It handles communication with the Google Gemini API.

## Frontend

The chat interface is implemented in `pages/index.js`. It allows users to send messages and display responses from the Gemini API.

## Deployment

To deploy, build the application with `npm run build` and then start the server with `npm start`.
