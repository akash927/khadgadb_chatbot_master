
# khadga_chatbot Application
This is a simple chatbot app. Here we basically answer the usually asked questions. We have uploaded a few quesries on a database. Here in this application,the backend receives the question and finds the question on the database and checks for the reply and sends it to the front end. We have used MERN stack to do the given application.
The questions on our database are:
Hello,
How are you?,
What is your name's meaning?,
Hi,
What is your name?,
Tell me a joke,
What languages you speak?,
Are you a robot?,
What's up?,
Good morning,
Good afternoon,
Good night,
Good afternoon,
Tell me something,
Ok,
Okay,
Yes,
I'll do that now,
Thank you,
Good bye,
How can you help me?,
What can you do?,
You are funny,
Do you love me?,
I love you,
Do you like people?,
You are cute,
You are beautiful,
You are handsome,
Do you have a hobby?,
You are smart,
You are clever,
You are intelligent,
You are annoying,
You are boring,
You are bad,
You are crazy,
I want to speak to a human,
I wan the answer now,
Are you a human?,
Where do you live?,
Are you expensive?,
How many people can you speak to at once?,
How is your day going on?,
Are you AI?,
Would you conquer the world?,
When will you die?,
Kill yourself,
Which is your planet?,
Where are you from?,

Hope you like our project and before starting make sure you meet the below pre-requisites.
# MongoDB Setup
Open MongoDB Compass and connect to the localhost:27017
And create a chat_khadga and users as collection
Import File KhadgaDB.json

# Backend Setup 
Go to Backend Folder
Switch to terminal, type “npm init -y” to create a package.json file.
Open it in Visual Studio Code or any text editor that you prefer.
If nodemon is not installed on your computer hit 
	“npm install nodemon -g“
Install dependencies by 
	“npm install express mongoose dotenv”
	“npm i cors”
Run “npm start” in the terminal to start the application.

# Frontend Setup
Create a new folder in a different place on your computer.
Hit “npx create-react-app chat-cosey-front” and wait for a while.
After the process completes, go to the chat-cosey-front folder and open it in Visual Studio Code.
In the Integrated Terminal of VS Code, type “npm i react-router-dom sweetalert2 axios” to install the dependencies.
Go to the backend folder, and open cmd in it.
Type “npm i cors” there. Go to app.js and add “app.use(require(‘cors’)());” below the “app.use(express.urlencoded({extended: true});“.
Hit npm start in the terminal to start the backend.

Thank you for showing interest in my repository!!!
