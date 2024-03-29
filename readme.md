## Features

- Users can sign in and register using Google.
- Users can select their role during registration as either a creator or student.
- Users can like, comment on the videos and share videos publicly (No auth required)
- Users can reply to existing comments with infinite nesting allowed.
- Each Video is marked as Viewed once a User watches 20% (just a threshold) of the video.
- Allowed creators to upload videos which are strored in an AWS S3 Bucket.
- Videos are streamed in chunks and fetched from the S3 Bucket.
- Application is deployed using AWS EC2 Instance.
- Clean and responsive user interface.
- Used MVC architecture in the backend design.

## Technology Stack

- MongoDB
- Express.js
- EJS Template Engine (For Frontend)
- Node.js

## Setup

1. Clone the repository from GitHub.
2. Run `npm install` to install all the dependencies.
3. Create a keys.js file in config directory and define the following keys
   - `mongoURI`: Connection URL to MongoDB Database
   - `googleClientID`: Google OAuth Credentials Client ID
   - `googleClientSecret`: Google OAuth Credentials Client Secret
   - `awsAccessKeyID`: AWS IAM User (with Access to S3 bucket) Access Key ID
   - `awsSecretAccessKey`: AWS IAM User with Access to S3 bucket Access Key Secret
4. Run `npm run dev` to start the server.
5. Vist `http://localhost:3000/` on your browser




#   l e a r n f l o w _ p r o j e c t  
 