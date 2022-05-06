# Course Resource Library - Spring 2022

This is edit of the prior project done by the former Team 3<br/>
All of our changes will be done based off of the source code supplied to us

Team 4:<br/>
Samuel Acra, Yashi Yadav, Ive Bigirimana, & Cameron Wilder

--- 

# Our Goals
1.  To implement separate login methods for the following:<br />
        &emsp;Students<br />
        &emsp;Instructors<br/>
        &emsp;Admins<br/>
2.  To allow the above register for their assigned roles

--- 

# To Register
1.  To register successfully  under the "Student" category:<br/>
        &emsp;Email: `CS360TestStudent@gmail.com`<br/>
        &emsp;Password: `CS360`<br/>
        &emsp;Role: `Student`<br/>
    This will take you to a confirmation page
1.  To register successfully  under the "Instructor" category:<br/>
        &emsp;Email: `CS360TestInstructor@gmail.com`<br/>
        &emsp;Password: `CS360`<br/>
        &emsp;Role: `Instructor`<br/>
    This will take you to a confirmation page
1.  To register successfully  under the "Admin" category:<br/>
        &emsp;Email: `CS360TestAdmin@gmail.com`<br/>
        &emsp;Password: `CS360`<br/>
        &emsp;Role: `Admin`<br/>
    This will take you to a confirmation page

---

# To Login
1.  To login as a Student:<br/>
        &emsp;Email: `CS360TestStudent@gmail.com`<br/>
        &emsp;Password: `CS360`<br/>
2. To login as an Instructor:<br/>
        &emsp;Email: `CS360TestInstructor@gmail.com`<br/>
        &emsp;Password: `CS360`<br/>
3. To login as an Admin:<br/>
        &emsp;Email: `CS360TestAdmin@gmail.com`<br/>
        &emsp;Password: `CS360`<br/>

--- 

# Instructions on how to deploy
We will recommend the same method of deployment that was recommended to us:

1. Clone the repository
2. Edit it as you intend to, as this is just the client portion and no-server portion was picked.

The recommended framework is Express in Node.js as that is easy to setup on your own

If you do with to deploy with Express, here is a guide on how to setup your site
1. Starting a new Node project, you are expected to have a server of some sort, but a simple local server can do just fine
2. Ensure you are running the proper versions of Node (NPM) and Git on your machine/server
3. In command line, run `git init` to create all the needed server files 
4. Create a starting JS file to act as your server, and ensure it is linked as a start case in your package.json file 
5. Create a folder in which you intend to store your files
6. Ensure Express is installed, instructions found here: https://www.npmjs.com/package/express
7. Setup Express in your main JS file

```
const express = require('express');
const app = express();

app.use(express.static('the_relative_path_to_your_page_storage_file')); 

app.listen(your_port or 3000)
```

8. After setting, you can run `npm start` in your command line
9. Going to your sites domain, or localhost, you can view every file as intended

Due to the project being primarily client based, there is no server-aspect to deploy so you merely have to just clone the files to a local folder
