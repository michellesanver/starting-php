# Chapter 2 video 8: Run the script
Now that you have your hello world script, let's run it! Open your terminal and write php index.php. That is the most straight forward way to run a PHP script. You will see hello world in there! But PHP is often ran in the browser. To communicate with the browser, we need a web server, like we explained in an earlier video. Lucky for us, PHP comes with a built in web server.

To run the web server we first ensure that we are in the correct place in the console. Use ls and cd to see where you are and move to the right directory. Or you can use cd /your/path/here to move there directly. For me I would write cd ~/... 

Then write the command "php -S localhost:8081" then you will see that the server is running and you can go to localhost:8081 in your browser. Hello world! 