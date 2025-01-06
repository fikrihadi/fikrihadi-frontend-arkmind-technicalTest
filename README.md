Frontend Setup Instructions
To set up the frontend of the project, follow these steps:

Install Dependencies
First, install all the necessary dependencies using npm. Run the following command in your terminal:

bash
Copy code
npm install
This will install all required packages listed in the package.json file.

Configure Environment Variables
Before running the application, make sure to configure your database credentials. These can be set in the .env file located at the root of your project.

Open the .env file and update the following values with your database credentials:

makefile
Copy code
DB_HOST=<your-database-host>
DB_PORT=<your-database-port>
DB_USER=<your-database-username>
DB_PASSWORD=<your-database-password>
DB_NAME=<your-database-name>
Start the Application
Once you've installed the dependencies and configured the environment variables, you can start the development server. Run the following command to launch the frontend application:

bash
Copy code
npm run dev
This will start the application on your local development server (usually accessible at http://localhost:5173).