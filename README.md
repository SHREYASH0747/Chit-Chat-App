# Chit-Chat-App

GitHub :  https://github.com/SHREYASH0747/Chit-Chat-App

Here are the installation commands for setting up the chat application:
Server Installation:
1.	Change directory to the server folder:
cd server
2.	Install server dependencies:
npm install
3.	Set up environment variables by creating a .env file in the server directory and adding the following variables:

     MONGO_URI= 
     JWT_SECRET=
     ADMIN_SECRET_KEY=  
     NODE_ENV=development
     CLIENT_URL=http://localhost:3000
     CLOUDINARY_CLOUD_NAME=
     CLOUDINARY_API_KEY=
     CLOUDINARY_API_SECRET=
4.	Start the server in development mode:
npm run dev
Client Installation:
1.	Change directory to the client folder:
cd client
2.	Install client dependencies:
npm install
3.	Set up environment variables by creating a .env file in the client directory and adding the following variable:
4.	VITE_SERVER=http://localhost:3000
5.	Start the client application in development mode:
npm run dev

