Frontend Setup Instructions 🚀
Welcome! Here’s a simple guide to get the frontend of the technical test for fikri hadi up and running on your machine  
1.  Install Dependencies 📦
The first thing you need to do is install the project dependencies. To do this, open your terminal, navigate to the project folder, and run the following command:
: npm install : 
This command will download and install all the necessary libraries and packages needed for the project. 🔽

2. Configure Environment Variables ⚙️
   Before you can start the application, you need to configure your database credentials. These are stored in a special file called .env. 🔑
   => Open the .env file located at the root of your project.
   => Add or update the following environment variables with your own database credentials:

  DB_HOST=<your-database-host>
  DB_PORT=<your-database-port>
  DB_USER=<your-database-username>
  DB_PASSWORD=<your-database-password>
  DB_NAME=<your-database-name>

3. Start the Application 🚀
   Once the dependencies are installed and the environment variables are set, you're ready to launch the application! To start the development server, simply run:

   : Npm Run Dev :

   This will start the app on your local machine (typically accessible via http://localhost:5173). 🌍


Troubleshooting 🛠️
If you encounter any issues with dependencies, try running npm install again.
If you face problems with your database connection, double-check the values you’ve added to the .env file to ensure they're correct.
  
