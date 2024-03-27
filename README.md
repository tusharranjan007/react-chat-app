Zest - Real Time chatting application

In order to build the project run the below command:
npm run build

In order to run the applocation run the below command:
npm  start

This is a react application which requires node to be installed on your system.
If node is not present in the system then please use the below website to install the system.

https://nodejs.org/en/download/

Once installed please open command prompt and type the below command:

node -v

OR

npm -v

**Important**
In order to run the application in local machine then the socket.io connection url should be changed.
As of now the code is connected to cloud and deployed with cloud configuration.

In order to change the socket url please navigate to:

frontend/src/context/SocketContext.jsx - On line "18"

Then change the url:

From

"https://react-chat-app-zest-prod.onrender.com/"

To:

"http://localhost:5000"
