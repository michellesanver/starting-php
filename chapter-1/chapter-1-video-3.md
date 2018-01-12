# Chapter 1, Video 3: A web page behind the scenes

### Description
Simplified Overview of how it works when you go to a website.
If you feel you need an overview again, have a look at this video again.

Goal: Have a simple overview and understanding of how web servers work. 

Questions:
- What is a server?
- What is HTML? 

---- 

When you enter a link in a browser: The browser needs to know where to go to get the content for you. It talks to another machine over the Internet, which similarly to a post address, has the address of the link you requested. That machine is called a "server". The server is in charge of reading the request that the browser made. 

The request includes information about which type of content you want, which language you want, and you also send details about the browser and location, among other things. 

On the server you have software that handles the request you made. This software is called a "web server". Two of the most popular web server software used today are called "nginx" and "apache", we will go into this in more detail later. They both work well with PHP.

The web server will handle the request, and if the requested page has PHP code in it, it will run that code. 
When PHP runs the code it can return HTML to the web server. [EXPLAIN HTML]
It can also communicate with other systems like storage solutions, such as a database [EXPLAIN DATABASE] to read or save information.
Then the web server takes the HTML that we defined in the PHP code and returns it to the browser in a response.

Now the browser takes that response and displays that to you, it can be the HTML, including resources such as text, images and videos.

![Web server process](webrequest.png)