# Real-Time Voice Web Application - Voice Rooms
## Description
This real-time voice web application allows users to create profiles, join voice rooms of different types (open, social, private), and engage in live discussions with features like hand raise and controlled speaking permissions.

## Features
- User-friendly UI designed using Figma for intuitive navigation.
- Frontend developed with React.js, Redux, and core CSS for an interactive experience.
- Backend powered by Node.js and Express for efficient server-side operations.
- MongoDB used to securely store user profiles and voice room data.
- Phone/email authentication with OTP for account creation and login.
- Creation and management of voice rooms with varying access levels.
- Hand raise functionality for controlled speaking permissions in voice rooms.
- Dynamic system allowing room creators to grant speaking access to listeners.
- Real-time voice streaming enabling live discussions.
- Private voice rooms designed for university-style exclusive discussions.

## Tech Stack
- UI/UX: Figma
- Frontend: React.js, Redux, Core CSS
- Backend: Node.js, Express
- Database: MongoDB
- Containerization: Docker

## Installation
1. Clone this repository.
2. Navigate to the project directory: `cd codershouse-mern`.
3. Install dependencies: `npm install`.

## Running with Docker
1. Make sure you have Docker installed on your system.
2. Build the Docker image: `docker build -t voice-rooms-app .`
3. Run the Docker container: `docker run -p 3000:3000 voice-rooms-app`

## Usage
1. Access the application in your browser at: `http://localhost:3000`.
2. Create a profile with your phone or email and verify with OTP.
3. Browse and join different types of voice rooms.
4. Engage in live discussions and raise your hand to request speaking permissions.

## Contributing
We welcome contributions! To contribute:
1. Fork this repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Make your changes and commit: `git commit -m 'Add your feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Open a pull request.
