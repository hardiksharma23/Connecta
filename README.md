# Connecta

Connecta is a modern web application inspired by Google Meet, built with Next.js and powered by Clerk for authentication. It enables seamless video calls, meeting scheduling, recording, and screen sharing, leveraging the Stream API for real-time communication features.

## Features
- Video calls with high-quality streaming
- Schedule meetings with calendar integration
- Record meetings for later playback
- Share your screen with participants
- Secure authentication with Clerk
- Responsive and user-friendly interface

## Getting Started

### Prerequisites
- Node.js (v16 or higher recommended)
- npm or yarn

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/connecta.git
   cd connecta
   ```
2. Install dependencies:
   ```sh
   npm install
   # or
   yarn install
   ```
3. Set up Clerk and Stream API:
   - Create a [Clerk](https://clerk.com/) account and a [Stream](https://getstream.io/) account.
   - Get your Clerk and Stream API keys and add them to your environment variables (e.g., `.env.local`).
   - Example:
     ```env
     NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
     CLERK_SECRET_KEY=your_clerk_secret_key
     NEXT_PUBLIC_STREAM_API_KEY=your_stream_api_key
     STREAM_SECRET_KEY=your_stream_secret_key
     ```

### Running the App
```sh
npm run dev
# or
yarn dev
```

Visit [http://localhost:3000](http://localhost:3000) to view the app.

## Usage
- **Video Call:** Start or join a video call with a single click.
- **Schedule Meeting:** Set up meetings in advance and invite participants.
- **Record Meeting:** Record your meetings for future reference.
- **Screen Sharing:** Share your screen with others during a call.
- **Authentication:** Secure sign-in and sign-up powered by Clerk.

## License
This project is licensed under the MIT License.
