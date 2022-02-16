## Course Resource Library - Fall 2021

This project focuses on the client aspect of the project

Team 3: 
Nick Scoble, Sarina Lalria, Trusha Patel, & Yi-Shian Liu

--- 

# Instructions on how to deploy
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

# To Access the site
1. The default username is `CS360Test@gmail.com` and the default password is `CS360` 
"# CS360" 
