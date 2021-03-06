# Ms-teams-clone
Microsoft Engage Mentorship 2021 task
# WebRTC Based Video Chat App named __We-meet__

Simple Web Application that offer you to create video meeting room using WebRTC and Socket

> ## Before you use on your local computer

These instructions will help you run my app on your local system.

> ## Prerequisites (Important)

You have to install [Node.js](https://nodejs.org/en/) in your machine.

> ## Installing

After installing node clone the repo by using git

Install npm modules once by doing cd over the project folder on your favourite cli and using the code below.

```
npm install
```
An extra Know-point

[Nodemon](https://www.npmjs.com/package/nodemon) For automatically restarting the server as a dev dependency (optional)

```
npm i nodemon 

```

> ## Running the App

In your cli do the following

```
node server.js
     or
nodemon server.js

```

> ## Deployment

For deploy the project I use [heroku](https://heroku.com)

[We-meet](https://we-meet-peeps.herokuapp.com/)

> ## Tech Stack/ Frameworks Used

-   [Node Js](https://nodejs.org/en/) - The Backend
-   [Peer JS](https://peerjs.com/) - PeerJS simplifies WebRTC peer-to-peer data, video, and audio calls.
-   [SocketIo](https://socket.io/) - For realtime communication
-   [NPM](https://www.npmjs.com/) - Dependency Management
-   [GIT](https://git-scm.com/) - Used for version control
-   [Heroku](https://heroku.com) - Used to Deploy Node.js applications
-   [Mondodb Atlas](https://www.googleadservices.com/pagead/aclk?sa=L&ai=DChcSEwjxheGAteDxAhXFrZYKHeYmDmYYABAAGgJ0bA&ae=2&ohost=www.google.com&cid=CAESQOD2MVJtXM4gAvx00zp1oY8UX2v2aUWmRXOC_h4Rw-LZPwOg8NS9UrglvF5woZx4waUyFJj7wUKTsRglnZ4IhKg&sig=AOD64_3dOnGCATA_i1H0iWi2r14-7y4f7Q&q&nis=1&adurl&ved=2ahUKEwiR39aAteDxAhWRyzgGHY5RBasQ0Qx6BAgCEAE) Used Mongodb Atlas for the database.
-   [Passport](https://www.passportjs.org/docs/) - Used passportjs for the user authentication.


<!-- This is a blockquote -->

> ## Features
* User Authentication
* Group Video Calling Features
* Join the meeting by pasting the meeting link.
* Waiting room.
* Video Call Features
    1. Video/Microphone On/off.
    2. Invite a user by pasting the email.
    3. Real-time chat features.
    4. Screen sharing.
    5. Video meeting recording.

Note: To know better about how to use the app, follow this [ppt](https://drive.google.com/file/d/1vZlflUNOfekE3zpmkqevnge-wzn125jJ/view?usp=sharing)
 or
 you can use this [video demo](https://drive.google.com/file/d/1C0HzmmDXAip5_hpMyUtCPVvGtNImGB6u/view?usp=sharing)
 
 ** Note: If after running for the first time, if gives not able to deserilaize related error. 
    Dont worry just repeat the node server.js command once again it will work.
