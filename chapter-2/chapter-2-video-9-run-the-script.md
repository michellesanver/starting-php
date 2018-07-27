# Chapter 2 video 9: Run the script
Now that you have your hello world script, let's run it! First check if you have PHP installed by opening your terminal and writing "php --version". If you don't have PHP, or the version is really old, we recommend that you install the latest version. See the video for installing PHP specific to your operating system.

Now that PHP is installed and you know which version you are running, let's run the script in the most straight forward way. We first have to ensure that we are in the correct place in the console. Use ls and cd to see where you are and move to the right directory. Or you can use cd /your/path/here to move there directly.

Then when we are in the right folder with index.php listed when we write "ls" we can execute our script with PHP by writing "php index.php". 

You will see hello world in there! This is a way to run scripts in the console, but PHP is mostly used as a web language so then we need a web server to see it in the browser. We explained web servers in an earlier video if you need a refresher. (link the video) Lucky for us, PHP comes with a built in web server! 

To run the built in web server we can use the command "php -S localhost:8081" then you will see that the server is running and you can go to localhost:8081 in your browser. Hello world! 