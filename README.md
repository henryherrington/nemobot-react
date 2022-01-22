<h1 align="center">Nemobot Labs</h1>
<div align="center">
  <img src="https://raw.githubusercontent.com/henryherrington/nemobot-labs/main/readme-images/nemobot-labs-chat.png" height="75%" width="75%" margin="auto">
  <p>The main Nemobot Labs page, with an updated interface to chat with Nemobot</p>
  <img src="https://raw.githubusercontent.com/henryherrington/nemobot-labs/main/readme-images/nemobot-labs-editor.png" height="75%" width="75%" margin="auto">
  <p>A new series of code editors to customize Nemobot program code. Each pane corresponds to a different section of a standard Nemobot program.</p>
  <img src="https://raw.githubusercontent.com/henryherrington/nemobot-labs/main/readme-images/nemobot-labs-about.png" height="75%" width="75%" margin="auto">
  <p>The new Nemobot Labs about page.</p>
</div>

## About
Nemobot Labs is a platform that allows users to learn JavaScript by creating their own chatbot programs. I worked on part time during the summer of 2021, expanding on my work with Nemobot the previous summer. I rebuilt this version using React to drastically improve maintainability. I also included on online code editor in which students can write programs which can then be immediately run on Nemobot. All of this experimental student code resides exclusivley on the client side so that it cannot interfere with server operations.

## Set up
1) Clone or download the repository
2) Install dependencies with npm install
3) Set up Google Cloud credentials in an environment variable to support Google Dialogflow. This step requires you have access to a working Dialogflow backend for Nemobot. For access, please contact the owner of this repo or Nautilus Software Technologies. Follow the instructions here for more details on setting up GC credentials.
4) Run the server `with node server.js`
5) Run the React frontend with `npm start`
