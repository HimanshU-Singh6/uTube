# YouTube-like Backend Project

This is a YouTube-like backend project built using Express.js, MongoDB, and Node.js. The backend provides functionalities to manage user accounts, videos, comments, and likes, simulating a YouTube-like platform.

## Features

- **User Management**: Register, login, and manage user accounts.
- **Video Management**: Upload, edit, and delete videos.
- **Comments**: Add, edit, and delete comments on videos.
- **Likes**: Like and unlike videos.
- **Playlists**: Create and manage playlists of videos.
- **Search and Filter**: Search for videos and filter by categories, tags, or other criteria.

## Technologies Used

- **Express.js**: A minimal and flexible Node.js web application framework for creating APIs and web servers.
- **MongoDB**: A NoSQL database for storing user data, videos, comments, and other relevant information.
- **Node.js**: A JavaScript runtime built on Chrome's V8 JavaScript engine for building scalable network applications.

## Installation

1. **Clone the Repository**:
   ```bash
   cd youtube-backend
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Set Up MongoDB**:
   - Install MongoDB and start the MongoDB server.
   - Create a new database for the project.

4. **Configure Environment Variables**:
   Create a `.env` file in the root of the project with the following content:
   ```plaintext
   PORT=8000
    MONGODB_URI=
    CORS_ORIGIN=*
    ACCESS_TOKEN_SECRET=chai-aur-code
    ACCESS_TOKEN_EXPIRY=1d
    REFRESH_TOKEN_SECRET=chai-aur-backend
    REFRESH_TOKEN_EXPIRY=10d

    CLOUDINARY_CLOUD_NAME=
    CLOUDINARY_API_KEY=
    CLOUDINARY_API_SECRET=
   ```

5. **Run the Application**:
   ```bash
   npm start
   ```


## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## Acknowledgements

- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Node.js](https://nodejs.org/)

---