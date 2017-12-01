# Beginner PHP Course

## Chapter 1, Video 3: A web page behind the scenes

### Description
Simplified Overview of how it works when you go to a website.
If you feel you need an overview again, have a look at this video again.

Goal: Have a simple overview and understanding of how web servers work. 

---- 

### Text
When you enter a URL in a browser: It connects to the web server that hosts that website. The server is then in charge of reading the request that the browser made. 
The request includes information about which type of content you want, which language you want, and you also send details about the browser and location, among other things. 

On the server you have software that handles the request you made. This software is called a "web server". Two of the most popular web servers used today are nginx and apache. They both work well with PHP.

The web server will handle the request, and if in the requested page there is PHP code it will execute that code. 
When PHP executes the code it can return HTML to the web server. 
It can also communicate with other systems like storage solutions, such as a database to read or save information.
Then the web server takes the HTML that we defined in the PHP code and returns it to the browser in a response.

Now the browser takes that response and displays that to you, it can be the HTML, including resources such as text, images and videos.