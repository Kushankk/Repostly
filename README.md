Repostly
Revolutionizing Video Distribution Across Platforms

Repostly is a video distribution platform that simplifies the process of sharing content across multiple platforms. With Repostly, users can upload a video once and post it seamlessly to TikTok, YouTube Shorts, and Instagram, saving time and effort for content creators.

Features
🌟 Multi-Platform Posting: Upload a video once, and Repostly automatically posts it to TikTok, YouTube Shorts, and Instagram.
🔒 OAuth2 Authentication: Secure login system ensuring user privacy and data protection.
⏱️ Real-Time Status Updates: Track the progress and status of your video uploads and postings in real time.
📂 AWS-Powered Storage: Securely store your videos using AWS S3.
Tech Stack
Repostly is built with modern, scalable, and efficient technologies to provide a seamless user experience.

Frontend:
React.js: For a dynamic and responsive user interface.
TypeScript: Ensures reliable and maintainable code.
Bootstrap: For a sleek and mobile-friendly design.
Backend:
Node.js: To orchestrate video uploads and API communication.
AWS Lambda: Handles platform-specific API integrations with serverless efficiency.
Database & Storage:
AWS S3: For secure and scalable video storage.
AWS DynamoDB: Tracks video upload and posting statuses.
Getting Started
Prerequisites:
Node.js (v18 or higher)
AWS CLI configured with appropriate credentials
Git installed on your local machine
Setup Instructions:
Clone the Repository

bash
Copy code
git clone https://github.com/your-username/repostly.git
cd repostly
Install Dependencies
Navigate to each directory and install dependencies:

bash
Copy code
# Frontend
cd frontend
npm install

# Backend
cd ../backend
npm install
Environment Configuration
Create .env files for both the frontend and backend with the following variables:

Frontend (frontend/.env):

arduino
Copy code
REACT_APP_API_BASE_URL=http://localhost:5000
Backend (backend/.env):

makefile
Copy code
AWS_REGION=your-region
AWS_S3_BUCKET=your-s3-bucket-name
AWS_DYNAMODB_TABLE=your-dynamodb-table-name
OAUTH_CLIENT_ID=your-oauth-client-id
OAUTH_CLIENT_SECRET=your-oauth-client-secret
Run the Project

Frontend:
bash
Copy code
cd frontend
npm start
Backend:
bash
Copy code
cd backend
npm start
Access the App
Open your browser and navigate to:

arduino
Copy code
http://localhost:3000
GitHub Actions
Repostly uses GitHub Actions for CI/CD:

Build: Verifies the project builds successfully on each commit.
Test: Runs automated tests to ensure quality.
Deploy: Deploys the application to AWS S3 and Lambda for production.
Workflows are defined in .github/workflows/.
