<h1  align="center">LaunchDarkly - SE Homework Assignment 📝</h1>

<p  align="center">
Credits to <b>javascriptbear</b> for providing the sample app <a  href="https://github.com/javascriptbear/todo_react_app">todo_react_app</a>.
</p>

## This implementation was designed to demonstrate a usecase of LaunchDarkly feature flags.
Please follow the steps below to run the implementation locally as no live demo version is available at the moment.

## Instructions:
 - Download and install **Visual Studio Code** (VSCode) by <a  href="https://code.visualstudio.com/">clicking here</a>.
 - Download and install **Node.js** by <a  href="https://nodejs.org/en/download/">clicking here</a>.
 - Install **Yarn** (our great Package Manager)
	 - Open VSCode and select **Terminal** located in the top menu bar.
	 - Select **New Terminal**.
	 - Type the command `npm install --global yarn`. 
 - Access the <a href="app.launchdarkly.com">**LaunchDarkly Dashboard**</a> and generate a new Client-side ID. 
 - On VSCode, open the App.js located in the folder "src", look for "clientSideID" and replace the value with the newly created ID.
 - On LD Dashboard, navigate to **Feature Flags** and select **Create Flag**. The key should be named as **EnableToDo** (note: this value is case-sensitive).
 - Open a new terminal and run the command `yarn && yarn start`. The required dependencies will be fetched and the application will open up shortly in your default browser.
 Alternatively, you can run `yarn`to download the dependencies followed by `npm start` to start the application.
 - You are all set! Turn on the **Enable To Do** flag to roll-out the new feature. The New Task button should be available instantly. To roll-back turn off the flag.
 
