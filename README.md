# CS208 Full Stack Project - TODO Application
 - Name: Grace Singpraseuth
 - Github: [https://github.com/gracesingpraseut](https://github.com/gracesingpraseut)
 - Term: Spring 2026

 ## Project Description

 This is a full stack web application built using Node.js and MySQL. The application allows users to manage a list of tasks. Users can add tasks, edit them, delete them, and mark them as completed or not completed.

## Install the Database
To set up the database, run the install script:
```bash
./setup_scripts/install_db.sh
```

## Create the Database Tables
Run the following command to create the database and tables:
```bash
sudo mysql -u root -p < ./setup_scripts/create_demo_table.sql
```

## Install Dependencies
Install required packages:
```bash
npm install
```

## Run the Application
Start the server:
```bash
npm start
```

## Access the Application
On Codespaces, you can access the application by forwarding port 3000. Open the forwarded port in your browser to view the application.

