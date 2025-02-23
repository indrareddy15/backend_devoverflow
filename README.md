# Dev Overflow

This is a Dev Overflow built using Node.js, Express, MongoDB, and Cloudinary.

## Features

- User authentication and authorization
- Post questions and answers
- Upvote and downvote questions and answers
- Comment on questions and answers
- Upload images using Cloudinary
- Search functionality

## Technologies Used

- Node.js
- Express
- MongoDB
- Mongoose
- Cloudinary
- Passport.js (for authentication)
- EJS (for templating)
- Bootstrap (for styling)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/backend_devoverflow
    cd devoverflow-clone
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Set up environment variables:
    Create a `.env` file in the root directory and add the following:
    ```env
    PORT=3000
    MONGODB_URI=your_mongodb_uri
    CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
    CLOUDINARY_API_KEY=your_cloudinary_api_key
    CLOUDINARY_API_SECRET=your_cloudinary_api_secret
    SESSION_SECRET=your_session_secret
    ```

4. Start the server:
    ```sh
    npm start
    ```

5. Open your browser and go to `http://localhost:3000`

## Usage

- Register a new account or log in with an existing account.
- Post questions and provide answers to existing questions.
- Upvote or downvote questions and answers.
- Comment on questions and answers.
- Upload images to your posts using Cloudinary.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
