# Video Scripts
Goal: From no programming ever to be able to go to a symfony/zf/laravel getting started page and able to start a project.

## Chapter 1: Introduction
### Chapter description
Learn what this course is about, who we are and the very basics of what PHP and the Internet is.

## 1: Expectation Management
### Description
We’re saying hello and telling you what you can expect from this course.

### Video text
M: Hi, I'm Michelle.
D: And I'm Dorian.
M: I have been doing PHP since year 2000 when I was 12 years old, so that means I've been growing up with PHP.
D: I've been using PHP for more than a decade, in various projects from very small (fits in a Tweet) to huge (hundreds of thousands lines of code).
M: Speaking of working with PHP, that’s what we both are doing at Liip - a digital company in Switzerland, where we are using PHP on a daily basis.
D: We started this course because we wanted to help our apprentices learn PHP. While looking for resources suited for absolute beginners, we thought we could contribute a different perspective of learning PHP. Since we benefit from and contribute to open source at Liip, we want to share this philosophy with everyone. Our goal is to teach you everything you need to know so that you can start a PHP project of your own.
M: During this course you will build a website, namely the php tutorial website that is linked in the video description. In fact, you might be on it right now, if you are not directly watching this on YouTube. The course is designed to watch from start to finish, and to use the videos as reference material, for later.
D: You don't need any programming experience before diving into this course. It's approachable for anyone. If you already have some experience, just skip ahead when we cover something you already know. All you need is a computer, an internet connection and you are good to go. Specific requirements, like having a software installed on your computer, will be mentioned in the video’s description along with instructions to get you up and running.
M: In this course you will obviously learn PHP as a programming language. To learn PHP we will also teach you how the internet works and how websites are built. We will briefly cover data storage and some of the tools that you need. We will also share common practices that will help you along the way

# 2: Programming
### Description
You’ve probably heard this word already - programming. But what is it, and why does it matter ? Programming is the skill one’s need to create software. And you might have noticed; software is everywhere these days.

### Video text
M: In today’s world, software is everywhere. If you look around you, you see your TV that has software in it. Train systems have software to make them not collide. The machines at the hospital all have software in them to make them work precisely and for you to survive. Without software our modern world would not exist.
D: Your smartphone is a computer that fits in your pocket, and it’s powered by software. When you’re withdrawing money from an ATM, that screen where you enter the amount? There’s software in there. Even something as simple as a digital alarm clock has software on it. And when you learn programming, you’re on your way to becoming a software wizard; like Neo in The Matrix movie (Link to the movie on IMDB). It doesn’t get any cooler than that, right ?
M: You can program a website like we do in this course. But you can also control your home with home automation. Or build a simple robot such as this cute little one [show robot].

# 3: A web page behind the scenes
### Description
A simplified overview of what happens when you browse a website.

### Video text
When you type or click a link, such as <link to phptutorial> in a browser (like Safari, Firefox or Google Chrome), the browser will talk to another machine over the Internet, using the link as an address (similar to a post address). That machine it talks to is called a "server".
The server is in charge of responding to the request that the browser made. The request contains a lot of information, like the type of content you want, details about your browser and your location.
On the server, there is a software, called a “web server”, that handles this request. Two of the most popular ones today are called "nginx" and "apache". The web server reads the request and locates the content on the server that matches. If the content has PHP code in it, it will first execute the code and then it returns the output as a response.
Now the browser receives that response and displays it to you. The most common format of the response is HTML, which is a semantic way of formatting web pages that all browsers understand. It can contain information about what a paragraph is, what an image is and other things. It describes your content so that the web browser knows how to display it. It can include links to other pages or even videos.

# 4: PHP
### Description
A description of what PHP is and why we should use it when there are so many other programming languages out there, such as JavaScript.

### Video text
PHP is like the machinery behind a website. PHP can be used for anything that you see on a website and also for many things you don't see. It has become the web language of choice since 1998. It powers most of the web, large websites like Facebook, Wordpress, Wikipedia and Tumblr are written in PHP. Because of that, there are many job opportunities for PHP developers.
 
PHP is a scripting language, which means that you can take your code and just run it, no additional steps required. In other programming languages, you often have to compile the code first, and then run it. This can take time (https://xkcd.com/303/). 

PHP is like a meal from a take-away restaurant, ready to eat, while with a compiled language, you first have to put the meal in the oven to cook it. PHP can be run on all major operating systems, such as Mac OS X, Linux and Windows.

Of course there are many other programming languages out there, and PHP is often used with them. PHP is often paired with JavaScript for example. In a modern application, PHP rarely stands on its own.
Despite its popularity, PHP is in some cases not the most performant language. Outside of web applications, it is rarely useful. Another downside of PHP is that you can write your code in many different ways, which can be confusing to people, as it is not always consistent. But don't worry, we will show you how to deal with this.

PHP is open source and under active development, which means that anyone can come with suggestions to improve the software. If you have a good idea for improvement, chances are that it will happen! There are many pieces of PHP code out there that are also open source and can be used in your projects. To make that easier PHP has a great tool, called "composer", which you can use to implement other people code in your project.

The community is large with many meetups and conferences. You can go to http://php.net/conferences (show clickable url) to get an idea of conferences around the world. And http://php.ug (show clickable url) is a great resource to find user groups in your area. At user groups they are often very welcoming to developers learning PHP; such as yourself. It’s also a fun idea to find a mentor or friend who knows programming already. http://php-mentoring.org (show clickable url) is a good place to find a suitable mentor. 

Of course PHP also has a very cute mascot! [show elePHPant]

# Chapter 2: Hello World
### Chapter Description
In this chapter you will learn about git and GitHub, with a hands on approach. We recommend every programmer to use git. 

## 1: git ready!

### Description
What is git and why should we use it?

### Video text
When we started programming years ago we often had situations where we wanted to rewrite what we have, but save the old version. To do this we would copy the file, and rename the old file into file_old.php. This got out of hand quickly, and keeping history this way was very difficult to see which one was made when. Version control is there for us to solve this problem.
With version control it keeps track of all the versions that you have saved, so that you don't have to do that manually. You only see one version at a time. A version is like a snapshot of all your code at that moment in time. You can go between different snapshots as much as you like, and they are always there. You can also compare different snapshots and leave comments with each snapshot to see what changed when, and most importantly; why. When you leave a comment on a version think "Will I remember why in 6 months with this comment?". That comment is called a "commit message" in git. The snapshot is called a "commit".
Since all our versions are there, we never have to worry about work getting lost when we try out new ideas. We can also put our code on other computers with git. git can be your code backup system, so that if your computer breaks, you always have your code.
Version control systems is a basic tool used by professional programmers everywhere, not only in PHP. It doesn't matter if you have a huge project or a tiny one. If there's lots of people working, or only you: You benefit from it either way.

## 2: GitHub; Your code online
### Description
What is GitHub and why should we use it?

### Video text
GitHub is a code hosting platform for version control and collaboration, there are many of these platforms. Such as GitLab and Bitbucket. GitHub lets you and others work together on projects from anywhere. In fact, it allows you to connect with us! You, and all the people following this tutorial will be using GitHub. It is a common tool in the open source world, and very popular in the PHP community.

While GitHub is free to use, if you put code on GitHub it's publicly viewable in the free use model. You can have private code on there, but that will cost money. Having your code public is usually a good idea, unless you are working on secret projects. Letting other people see your code, means that they can come with suggestions or find errors. Publicly available code is often more secure than private code. You can add licenses to your public code, so that others can use it only in the way you specify. You can learn more about licenses in the linked resource. We will do everything publicly, as there's no secrets here...

You can also see GitHub a bit like a backup, because it is both on your computer and online. But the big point for us here is that: With GitHub we can collaborate. So let's get started right now! If you already have a GitHub account you can skip the rest of this video.

## 3: Create your GitHub repository
### Description
This video will walk you through creating a place for your code online, on GitHub.

### Video text
A repository can be seen as an online folder on GitHub, which not only stores the files, but also the history of it. This is where git comes in, like we explained in a previous video, git is used to keep versions of your files. Files can be anything, such as PHP code, images, videos, spreadsheets or text files.

So let's create the repository you will be using during this tutorial!

*VIDEO:* To create a new repository you click the + icon next to your username up here. Choose "New repository". The only things you need to fill in is the repository name, and let's create a readme file by default. A README.md file is the first file that a programmer reads when they go to your project. And the first one you can read if you go to someone else's project. It describes what the project is about, and how to install or use it. It is also for you to remember things about the project when you code. For instance you could have information on how to get the project running. You will thank your past self if you do this properly! This is why we choose to tick the box.
The rest can be left to default. Click create. You will now get to this screen, advising you what you can do next. Congratulations, you have created your first repository!

## 4: Your first pull request
### Description
Sharing is caring! We’re showing you how to request changes and collaborate on GitHub. 

### Video text
A big part of git and GitHub is collaboration. Let's see just how easy it is by creating your first pull request (often abbreviated “PR”). A pull request is you suggesting changes to one or several files.
VIDEO: First you go to [GitHub - michellesanver/starting-php](https://github.com/michellesanver/starting-php) which is the php tutorial repository. In there you will see I_WAS_HERE.md, click that file.

Then press the edit icon in the top right corner, and add your name to the file. Scroll down and add a commit message. A commit message is the description of the change that created a new version of the file. Every time you make a commit, it will be a new version of the file.

Press the commit button to save your changes. Behind the scenes GitHub now automatically creates a new copy of the phptutorial repository to your account with the change in it. Now you can suggest to merge your change into the main phptutorial repository. This suggestion is called a "pull request.". That way someone can look at the suggestions, and suggest changes, before they go into the final version.

Press the "Create pull request" button. If you have anything to tell us, feel free to add it here! Note that this information is public and anyone can see your message.

Now you can submit your changes by pressing the "create pull request" button. It can take up to a few days for us to accept your changes! When we have you will get a notification about it via GitHub, and your name or nickname will show up in the list! Congratulations, you have made your first open source pull request.

## 5: The terminal
### Description
The terminal is the thing you often see in the movies with the green text flowing by. We will introduce you to this friendly and useful tool, something every programmer tends to use.

### Video text
So now you have your empty repository on GitHub. To be able to work with the code on your computer, and sync it between your computer and GitHub you need to use git. There are many tools out there that can help you with this, but we will teach you the most basic way, by using the terminal. The terminal is often also called “console”, especially on windows. In this course we will refer to it as “terminal”. Depending on your background, you may already be familiar with the terminal, if not: Don’t worry! We will explain how it works. 

A terminal is an interface on your computer where you can write commands and see their output. This is a very useful tool for a programmer. You have probably seen a lot of movies with terminals, this is not how they look like in the "real world". It is just an interface, which doesn't require any previous knowledge or additional tools.

Depending on your setup, your terminal will look different.

M: Here is a terminal in OSX, I'm writing a command to list files in a directory.

D: And here I am writing the same command, on a Linux terminal.
You can install many programs that has commands for the terminal; one of them is git. 
 
Next, you will need to open your terminal (which might be show you how to open your terminal based on your operating system, and install git. Select the video (link it) for installing git that matches your operating system.

## 6: git clone; Your own local copy of the code
### Description
When you see code that you want to change online, we often make a local copy of the code to change it and then submit it again. This video will explain the concept of cloning, and how you do it. 

### Video text
Now that you have git, you can clone the repository you created in the previous video to start working with it. You do this by going to your repository on GitHub and then click the “clone or download” button, press the button to copy the URL. Then open your terminal. Write “git clone” and paste the url (purposely write “git glone” instead) and press enter. Thank you git! Yes, we meant “git clone”. When we make a typo in a git command, we often get useful hints on what we did wrong.

When you git clone the code will end up in a directory on your computer. By default it will be a new directory with the name of the repository. But you can also name the directory anything you want by writing “git CLONE url” followed by the name.

Now you want to change directory in the terminal to the one you just cloned. You do this by writing “cd” followed by the directory name. So “cd phptutorial”. Write “ls” to see your files again. If you see the readme file you created, all is good.

## 7: Editor introduction
### Description
An editor is where you write your code. We will introduce you to one of them here. 

### Video text
Now that we have our repository on our computer, we need to be able to edit the files. The application used to do this is called an "editor". There are many different editors available. In this tutorial we have chosen Atom [https://atom.io/]. It is an open source, free editor which works on all major operating systems. It has all the things a beginner in PHP needs. There are other editors which usually cost money, which give you more functions. They are not needed to produce good code, but they can help in your productivity.

For the next video, you will need to have Atom installed. We have made OS specific videos on how to install it (link videos). Once you have installed it and opened it, you can go on to the next video.

## 8: “Hello World!” script
### Description
Creating our first PHP script. 

### Video text
Open your code editor, atom. Go to the "File" menu and select open. Browse to the directory that you clones in a previous chapter. Click "open". You will now see your directory and your readme file in the sidebar to your left. Now we can create our new file. Go to the "file" menu again, select "new file" and you will see a new tab "untitled". Go to "File" again and choose "save". Ensure you are still in the phptutorial folder and enter "index.php", press save. Now you will see that file above the readme file.
Ensure that you save often! Remember the shortcut you see in the file menu. You can see that it's {shortcut} on {operating system}.

Congratulations! Now, finally, we get to write some PHP! All PHP code starts with the PHP tag. <?php. We need the tag so that PHP knows where the code starts, and what it should run. You will see in a later chapter how you can mix PHP with HTML.

Write “echo 'Hello World!';”. “echo” is a language construct that outputs text.

A PHP instruction always ends with semicolon, that way PHP knows when it's done with that instruction. If you forget it, PHP will output a "syntax error" telling you which line you probably forgot. You can see the line numbers on your left. Our echo instruction is on line 3.

The script runs from top to bottom and left to right. A lot like reading in english. Let's go run our code in the next video!

## 9: Run your PHP script
### Description
Running our first PHP script.

{TODO: Add resources here for installing PHP}

### Video text
Now that you have your hello world script, let's run it! First check if you have PHP installed by opening your terminal and writing "php --version". If you don't have PHP, or the version is below 7.0, you need to install the latest version.

Now that PHP 7.0 or later is installed, let's run the script in the most straightforward way. We first have to ensure that we are in the correct place in the terminal. Use ls and cd to see where you are and move to the right directory. Or you can use cd /your/path/here to move there directly. We want to see the “index.php” you created in the last video when you write “ls”. 

We can execute our script with PHP by writing "php index.php".
You will see “Hello World!” in there! This is a way to run scripts in the terminal, but PHP is mostly used as a web language so then we need a web server to see it in the browser. We explained web servers in an earlier video if you need a refresher. (link the video) Lucky for us, PHP comes with a built in web server (for development purpose only)!

To run the built in web server we can use the command "php -S localhost:8081" then you will see that the server is running and you can go to localhost:8081 in your browser. “Hello World!”

## 10: Commit and push, the git workflow
### Description
Let’s put our code online and use git for code history. 

### Video text
Now you have a repository, and you know how to run your code locally. Your code is only on your machine. If you go to GitHub and browse your repository, nothing is there yet.
A common workflow that programmers use is the following:
Write your code.
Add your code to git.
Commit the code in git, aka make a new version with a clear message.
Push the code to the remote repository, aka put the code online and ensure it's not only on your machine.
Now let's go into how to implement this workflow step by step. Open your terminal. Write "git status" this will show you a status of how your files are right now. Like on my screen you will see a list of untracked files. This means that you have files that are not yet in the git version control. It's time to add them. Write "git add (index.php the filename of the file we created earlier)". Now write "git status" again and you will see your file with a new status. It will say "new file". With add it is not a new version yet. So there's no commit yet! This is a very common thing to forget. So now we need to commit it. Write "git commit -m 'My first commit'" it will say "1 file changed". So now we created a new commit and git recorded the actual content of the file in a new version. You can see all your versions by writing "git log -n 5". The n stands for how many versions you want to see.
Now it's time to put your code and version history to GitHub! Write "git push" to push it to your remote. Now go to your GitHub repository and you will see your changes there. This workflow will often take some time getting used to, so don't worry if it seems like a lot now. It gets easier as we go!
 
# Chapter 3: HTML: Format your website & git tagging
### Chapter description
In this chapter you will create a simple page with a form, and make your index.php page look better. You will also learn how to keep track of different versions of your website, using git with tags.
##  1: HTML markup
### Description
The language of the browser is HTML. We will give you a short introduction, so that you can speak to the browser. And you will write some HTML and display it in the browser. 

### Video text
We know that PHP is a dynamic programming language, so you can define your own logic to express your content. When PHP speaks to a browser, it needs to speak the browsers language. Browsers by default speak “HTML”, so the output of PHP is usually either in HTML, or it is output as strings surrounded in HTML. 

This is all very abstract, so let’s look at it in a more practical way. 

Let’s open the index.php file that you created in chapter 2. In PHP files you can also express HTML. If you want to create a pure HTML file you should end the file with .html instead of .php.

Let’s write <p>Hello World</p> and run the script in your browser like you did in chapter 2, video 9. You can see that you only see the words “Hello World” and not the opening <p> tag and closing </p> tag (beware the additional slash) surrounding it. “p” tags stands for paragraph, like a paragraph of text. You don’t see the tag, because it is only used to speak to the browser, and the user will not need to see how we do that.

Let’s add a header to the page by adding <h1>Starting PHP</h1>. “h1” is an element that stands for “header 1”. This means it is the biggest header. See what happens if you change it to “h2” (remember to change both the opening closing tags).

Anything in angle brackets is called an HTML element. HTML has many elements that express different things. If you have a link the browser needs to know it is a link to make it clickable, if you have an image the browser needs to know it is an image to display it correctly, etc. 

HTML has a structured way for the entire document to be formed and for which elements belong where. Like a spoken language, you can see this as the “grammar rules”. Luckily for us, HTML has no grammatical tenses… 


So let’s look at the most basic grammar. The minimal HTML structure for a valid HTML page we know any browser will understand:

```
<!DOCTYPE html>
<html>
    <head>
        <meta charset=”utf-8”>
        <title>Starting PHP</title>
    </head>
    <body>
        <p>Hellö World!</p>
    </body>
</html>
````

`<!DOCTYPE html>` is a historical thing of HTML, and we no longer care about it in our modern world. Those are the shortest string of characters that counts to make your HTML valid. This weird grammar that stopped being taught in the 80’s and none of the new generation know what it’s about even though they see and use it, yeah, that’s DOCTYPE. 

The `<html>` element is to keep your page contained, it’s nice to start with `<html>` and get yourself in the mood of expressing markup! In HTML we have a `<head>` where all the information we don’t see but that the browser needs to render certain things correctly lives. Such as the <meta> element here. We see that it defines our charset to be “utf-8”. “charset” is short for “character set” and it is a way of expressing what kind of characters we can expect. “utf-8” has become a standard as it supports all characters of any natural language, including emojis! I’m afraid that if you want to write in “klingon”, you have to use another charset. We recommend that you use “utf-8” for all your code. So by defining “utf-8” it means that our umlauts (the little dots over the o) gets displayed nicely. As long as our browser knows what “utf-8” is, which it most likely does as it is a standard, it will read out our “Hellö” beautifully.

We additionally see in the head that we set the <title> element on our page, if you change the title you will see that it changes on the tab or in the top of your browser, wherever titles are displayed. That’s pretty neat! 

The `<body>` element is where you put everything you want the visitors of your page to see. This is where your content goes, such as our <p> paragraph. 

In the `<meta>` element you see that we have some definition inside of it, namely the charset. That is called an “attribute”. Many elements in HTML have attributes to help the browser further. 

If you want to mix HTML and PHP in one document, which we will do in the beginning of this course you will need to use the `<?php` tag for the browser to know that it has to speak to PHP now. 

We can change the paragraph to output “hello world” expressed in PHP like so: 
`<p><?php echo ‘Hello World’; ?></p>`

Remember to always close the PHP tag (using “?>”) when you mix HTML and PHP, so that the browser doesn’t get confused on what to do, and so that it knows that it can start talking HTML again. 

Of course it is pretty useless to express static content in PHP, as you can do that directly with HTML. But let’s say you want to display the current date. You can do that with PHP: 

`<?php echo date('c'); ?> `

`‘c’` tells php to display the date according to the “ISO 8601” standard. This is not something you need to remember right now, but if you’re curious you can read more about how to format your date here (http://php.net/manual/en/function.date.php). And as an exercise you can change ‘c’ to different things and see how the format changes. You can combine letters like ‘Y F’ for year and month.

To wrap-up this video: That is really all you need to know about HTML to build our website for the purpose of this course. There is of course a lot more to it, and we recommend that you read up more on what HTML can do so that you can build websites that every browser understands. 


Mozilla has a great interactive resource that you can use to learn more about HTML: https://developer.mozilla.org/en-US/docs/Learn/HTML

## 2: CSS markup
### Description
CSS is a way to express how your website should look. This will show you 
the basics.

### Video text
Once you’ve created your first HTML page and opened it in a browser, you’ll surely be very happy to see the result on the screen. Though let’s be honest; it might not look great. That’s because we’ve only been interested in the “structure” of the page so far (using HTML), not yet the design. CSS is here to provide a way to customize the look of a web page.

For example, let’s say you have a title “<h1>Starting PHP</h1>”. In most browsers, it will render by default as a big text with a bold (meaning heavy) font. It you want to change any of these specifications or tweak other ones (for example, changing the color), you’ll need CSS.

The basic syntax of CSS code looks like this : 

selector {
    attribute: value;
}

A selector is used to identify which HTML element you want to design. In our example, it would be “h1”. Another example could be “input[type=”text”]”, which would apply to any text form fields on the page.

An attribute is used to identify what design element you want to customize. Common examples include “color”, “font-size”, “margin-bottom” and so on.

Finally, a value is the value you want to give to the attribute, which could be “red” for the “color” attribute, “14px” for the “font-size” (“px” is a “pixel” unit) and so forth.

A complete example, that would change the “h1” element to be red and have an underline, would look like this :

h1 {
    color: red;
    text-decoration: underline;
}

Now, you might wonder where to put that code for it to take effect. There’s two ways :

Use the “style” HTML attribute, directly on a specific HTML element :

<h1 style=”color: red; text-decoration: underline;”>Hello World!</h1>

Here, the red color and the underline will only apply to this specific “<h1>” tag. Note that only the content of the brackets (between “{“ and “}”) is used here, and the “h1 {“ and “}” parts are absent. Also, the CSS code usually is written on one line in this scenario.


This method is only used on pages that require very few design customizations and should mostly be avoided on real projects.


Use external file(s) containing the CSS code (put the code example above in “style.css”) and embed it (aka load it) in the “<head>” section of the HTML document, using a “<link>” tag :

<link href=”style.css” rel=”stylesheet” />

Here, the red color and underline would apply to every “<h1>” tags in your page.

This method is used for most of the web pages you’ll encounter and is very powerful and flexible.

That is really all you need to know about CSS to build our website for the purpose of this course. There is of course a lot more to it, and we recommend that you read up more on what CSS can do so that you can build beautiful websites. 

Mozilla has a great interactive resource that you can use to learn more about CSS: https://developer.mozilla.org/en-US/docs/Learn/CSS
3: HTML forms: adding videos
Description
We need to add the content of the videos somewhere. The videos are all on YouTube. We will create the structure (HTML) of one of our forms for the admin part of the website, to add videos.
Video text
In video 1 and 2 of this chapter we learnt about HTML and CSS. Now we can use this knowledge to create a form so that we can add our YouTube videos as content to the website!

The very minimum a user needs is to know what the video is about (a title) and a description of the video content. Later on, we will need to split by chapters and such, to make it even easier for the user, but let’s start with the bare minimum.


This is what we need in our form to display the minimum video list to our users:
Video title
Video description 
Video link (to YouTube)

This form would be on a new page on our website, so we can create a new file for this page and call it “course.php” and open it in our editor.


In HTML, we express that we want to create a form with the “form” element. The form element takes some attributes that define the way the form behaves. The “method” attribute defines the way we send the form. We can either specify “post” or “get” - we’ll look at the difference between the two in chapter 4 (link video). Here we’ll use “post”. The “action” attribute tells the form: “Ok, when a user presses the button to send this form, where do I go?”. Its value is usually a path to a file, which can be the same as the one we’re displaying the form from, like we’ll do here.

<form action=”course.php” method=”post”> 
    <!-- Content goes here -->
</form>

Now, we need the fields of the form. Let’s start with the title field. To define a field where a user can enter input, you express it in HTML with the “input” element. To express that we want the user to enter text, we use the “type” attribute with the value “text”. We then give the field a name, so that we can retrieve the data from a specific field later on.


<input type=”text” name=”title”/>

Note that for the input, you need to close the element differently; it’s a self-closing tag. For the YouTube link field, it is just the same, but with another name:

<input type=”text” name=”youtube-link”/>

Then to add a bigger field where the user can write the description of the video, that can sometimes be a bit longer text, we need to use the “textarea” element.

<textarea name="description"></textarea>

So your minimal form will look like this: 
<form>
    <input type="text" name="title"/>
    <input type="text" name="youtube-link"/>
    <textarea name="description"></textarea>
    <button>Add the video!</button>
</form>

Now run this code and take a look at it in your browser. As we can see, it isn’t very pretty and all the fields are next to each other! Also we have no clue which field is “title” and which one is “youtube-link”. Let’s fix this with the “label” element. 

The label element and its “for” attribute define which label belongs to which form field, so that any user can find the correct field to write in, including a blind user using a screen reader. It requires that we add an “id” attribute to the form fields elements (input, textarea), as the “name” attribute is only used for retrieving the data.

You can look at the code below where we’ve added labels before each field, which is a big improvement. But they are all still in a row; this is where CSS comes in. 

To style our form, it’ll be easier to group our fields and labels together using a “div” element. 

<form>
    <div>
        <label for="title">Video title: </label>
        <input type="text" name="title" id=”title”/>
    </div>

    <div>
        <label for="youtube-link">YouTube Link: </label>
        <input type="text" name="youtube-link" id=”youtube-link”/>
    </div>

    <div>
        <label for="description">Video description:</label>
        <textarea id="message" name="description" id=”description”></textarea>
    </div>

    <div>
        <button>Add the video!</button>
    </div>
</form>

If you look at the form in your browser now, it is likely that you have the fields on their own lines, like I do. Note that we gave the “button” element the attribute “class” which is a way to tell this div apart from the others when we style it. 

To style it we can add the <style> element under header. 


First of all we would like all our labels to be aligned. Right now they have different size because they are different length text. In CSS we can define “label” to have the same size and alignment like so:

        label {
            display: inline-block;
            width: 130px;
            text-align: right;
        }

It already looks a bit less chaotic! It isn’t very nice that the input and textarea looks so different and aren’t the same width and aligned, so let’s give them some styling in common. By default textarea has a different font, so let’s ensure all of input and textarea use the same, that they are all 300px wide and that they have the same type of border. 

        input, textarea {
            font: 1em sans-serif;
            width: 300px;
            box-sizing: border-box;
            border: 1px solid #ccc;
        }

Much better! But it is a bit weird that the label for textarea is on the bottom and not the top, so let’s change the styling of that. 

        textarea {
            vertical-align: top;
        }

So beautiful! But the button isn’t aligned and the fields are very close to each others. Let’s define the left margin to be the same as the width of the labels to align it and space the fields a little bit. 

        button {
            margin-left: 130px;
        }

        div {
            margin-bottom: 10px;
        }

There we go! We can keep styling our form, but I think it looks good enough now. Feel free to play around with it, if you’d like.

Note that we have a form now, and we can write text into it, but if we press the submit button, nothing happens. We need PHP to make the form actually do something. We are going to look how to do that in the next chapter, chapter 4.

Don’t forget to commit your code in git at this step! Look at chapter 2 “Hello World” for more detailed information. 

<Show us commiting the code in the terminal, while going through what we do i.e. “so let’s open the terminal, write “git status” etc...> 

# Chapter 4: Basics of PHP
### Chapter description
In this chapter, you will learn about the basic concepts in PHP and you will make the “add video” form you created in chapter 3 do something.

## 1: Accessing the form data, in PHP
### Description
We’ll look at ways to access and use the data submitted from an HTML form with PHP.

### Video text
So we have the form in HTML, and we told the form to talk to “course.php” and send the provided data with the “post” method. Now, how does PHP can access the submitted data ?

Enter the world of predefined variables. There are variables that we define ourselves, starting with “$”. Predefined variables also start with $, but they are something that PHP defined for us, containing specific information. Typically, they are prefixed with an underscore too. There are many different predefined variables, but the one we will look at now is `$_POST`. In the `$_POST` variable is all the information sent within a POST request - which is what we receive from the form, so exactly the information that we need!

Let’s use the PHP function “var_dump” to look at the content of the `$_POST` variable (and an bonus “pre” HTML element surrounding it to make the output easier to read). Add this code before the opening tag of the “form” HTML element for example.

`<pre><?php var_dump($_POST); ?></pre>`

Refresh the page and you should see “array(0) { }”. Don’t worry about the curly braces and such, we will get into that later. The important thing to see is that when you enter information in the form and submit it again, you will then see the information you entered at the top of the page, formatted in the way that PHP receives it. This is what we will use. 

We can use the PHP function `isset` to figure out if a form field was filled. The code below will show the output of the `isset` function, which is either “bool(true)” (yes, “something” is set) or “bool(false)” (no, “something” isn’t set) :

`<pre><?php var_dump(isset($_POST[‘youtube-link’])); ?></pre>`

You can test it by refreshing the page; it should display “bool(false)”). Then, input something in the “YouTube Link” form field, submit and it should display “bool(true)”. Now, we’d like to tell PHP to do something only if the information is provided. This type of struct is called an “if statement”. You can read it in English like this: if (something is true) { THEN DO THIS }

As we could see, isset($_POST[‘youtube-link’]) was only true when we had submitted the form, so the things inside the curly branches will only happen if the form is submitted and the “youtube-link” form field is filled.

```
<?php
if (isset($_POST['youtube-link'])) {
    echo ‘<p>Thanks for providing PHP with a YouTube link that it can now use!</p>’;
}
?>
```

## 2: Primitive Data Types & Null
### Description
We’ll explore the different types of data that PHP can create, manipulate, evaluate and much more.

### Video text
To know what we should do with the data, we need to know which type the data is, and how PHP handles that type. 

The four scalar types in PHP are “string”, “boolean” (or “bool”), “integer” (or “int”) and “float” :

A string is any sequence of characters as text. 
A boolean is either false or true. 
An integer is a whole number such as “1” or “134”
A float is a decimal number such as “1,0” or “553,42”.

Any scalar type can be converted into another scalar type by using a feature of PHP called “casting”. Some examples :

The string “1234” can be converted to the integer 1234, because it is numeric.
The string “123a4” can not be converted to an integer, because “a” is not a number.
If you convert “1” to a boolean, you’ll get “true”. Try “0”, you’ll get “false”.

An interesting thing to note here: if you convert a string into a boolean, it will give you “true” as long as there are characters in that string, and “false” if the string is empty. So the string “false” will evaluate to the boolean “true”. There’s many small “quirks” like this one when converting types in programming in general, so be alert when using such features.

### Null
In PHP, when something does not exist, there is a special type for that called “null”. Null means that something is not set, it’s not there, PHP has no reference to it and will throw an error if you try to do something with it. This is why we often check if something is set before using it : to avoid an error. See what happens if we use the code in the previous chapter, without the “if-isset” condition around it. <Edit the code to not have the ‘isset’ and then show the site with an error>. We get an error because “youtube-link” is not set in “$_POST”. If we would put something in the youtube-link form field, it would be a string, and as we know a string if there is something in it, is always true, so it would evaluate to true and the code will work. Let’s enter something in the form and see the error disappear. <Enter something, and see the message as expected>

## 3: Arrays: A collection of data types
### Description
We’ll look at a specific data type in PHP : arrays, a collection of other data types.

### Video text
An array in PHP is a collection and is expressed with square brackets []. We saw the array earlier when outputting the $_POST variable. Let’s look at that again. <type var_dump($_POST);
In the code and look in the browser>. We see “array(0)” which means we have an array, with 0 things in it. If we now enter something in the form, we will see an array with one thing in it, a string. The string we entered. 

We can access values in an array with the square bracket notion. We know from the var_dump that $_POST is an array and that it has ‘youtube-link’ in it so let’s try to output that: echo $_POST['youtube-link'];

We get that undefined notice again! But if we enter something, it works. That’s because the array only has the youtube-link if there was a post request to the page from that form. Let’s see what happens if we define our own array with different types in it. You can throw anything you want into an array, including other arrays!

```
$array = ["banana", true, 23, 10.3, ['124', 123]];
var_dump($array);
```

If you put the <pre> html tag around your code you get a more readable output <put pre tag around and view the output>

So as we can see we have an array of 5 items, PHP always starts indexing items at 0 (most computers indexes do; it’s weird at first, but you’ll get used to it). So element 0 is a string called “banana”, 1 is the boolean “true”, 2 is an int with value 23, and 3 is a float with value 10.3, 4 is another array with two items, the string “124” and the integer 123. We can access the value of the array by using their keys. The keys is the numbers you see on the left hand side, starting at 0. echo($array[0]); will output “banana”. We don’t always want numbers as indexes to reference our array so we can use something called an “associative array” and define the keys ourselves. In an array the keys always have to be unique, so using an array like this has a higher risk of overwriting, so be careful when you do! It is however very powerful to have more readable code. Let’s have a look. Using the same data, we can add different keys to it to give the data meaning: 

```
$fruit = [
   'name'           => 'banana',
   'is_available'    => true,
   'amount_in_stock' => 23,
   'price'           => 10.3,
   'meta_data'       => [
       'bar-code-id' => '124',
       'internal-id' => 123,
   ],
];
```

What before looked like random number now looks like really useable data! We can use this on a website where we sell bananas to know if they are available, show how much they cost and how many we have left. We can also show the bar code so that a cash register can scan it if wanted, and the internal id so we can reference it in our system. Neat! Much nicer than having to remember that “2” means “amount_in_stock”. 

<var_dump and show the output with the names as you say the above>

Of course we can go one step further and give $fruit a name as well, and skip the ‘name’ element. 

```
$fruit['banana'] = [
   'is_available'    => true,
   'amount_in_stock' => 23,
   'price'           => 10.3,
   'meta_data'       => [
       'bar-code-id' => '124',
       'internal-id' => 123,
   ],
];
```

We can then easily add other fruit as well, such as pears. 

```
$fruit['pear'] = [
   'is_available'    => false,
   'amount_in_stock' => 0,
   'price'           => 3.2,
   'meta_data'       => [
       'bar-code-id' => '124fA',
       'internal-id' => 129,
   ],
];
```

Now we see clearly that this is a collection so we can rename the array to $fruits. <rename in editor> to represent all the fruits. Let’s `var_dump($fruits);` and look at the array. We see that we have banana and pear. This is useful data for us to output, we can look at $fruits and output all the information. Let’s use what we just learnt to store and output the information about our added videos in the next video’s. 

## 4: Storing information in a file
Now that we know how to get information from the form and how to read it, it’s time we store it somewhere so that we can save and output it on our page! The easiest way for us in PHP is to store it in a file.

We can use the built in PHP function “file_put_contents” for this. It is very useful because it will even make the file for us! YAY! “File_put_contents” takes a couple of arguments but the two that it demands it “file name” and “data”, we will use just these two arguments. 

`file_put_contents('videos.txt', $_POST['youtube-link'] . ',');`

The .dot notation in PHP is a way to put strings together, see the dot as string-glue. So we are putting the content of youtube-link and put a comma after each link so that we can separate them in “videos.txt”. Let’s try it out! 

<Run the script, go to the browser, enter something in the form, and then open the file and see it there, go to the browser enter something else and see that too>

Oops! We see that everytime we add something in the file, the first thing disappears, that’s not good. We want to save all the video’s! Let’s solve that. Let’s look in the PHP manual to see if there is any clue that we can use that helps us. 

<open the manual and read the part about the flags and the FILE_APPEND> ok so FILE_APPEND seems to be just what we need. Let’s add the flag and try again <add the flag, add videos on the website, see the file and see both videos> ok that looks better! Now we have the video’s in a file. Let’s see in the next video how we output the videos on the website. 

## 5: Loops: Adding content to our website
### Description
The website so far is not looking like much of a website. We are going to need more pages, and some content. Let’s look at adding content with loops and structuring the website a bit. 

### Video Text
The built in function to put data in a file is “file_put_contents”, the function to GET data from a file is intuitively named “file_get_contents” so let’s try that out. Let’s get the contents and then like before, var_dump to see what’s in it, so we know what types it is and how we should access the data.

```
<?php
   $videodata = file_get_contents('videos.txt');
   var_dump($videodata);
?>
```

We can see that all the data is one single string! We want just the video’s separately so we can output them in a list! We separate them by comma in the text, so how do we do that in PHP? You guessed it… There’s a function for that! It’s called “explode” it splits a string by a string into an array. 

```
$videotext= file_get_contents('videos.txt');
$videodata = explode(',', $videotext);

var_dump($videodata);
```

So here the first argument is “what do you want to split your data with?”, the delimiter. We decided to use a comma, so we specify that here, the second argument is the text we want to split so that would be `$videodata`, but let’s now call that $videotext, and the thing we get out now `$videodata`, and `var_dump` that instead. 

That looks like an array that we can use! It is split by video. But wait a minute… The last one is empty, let’s use PHP’s array_filter function to clean up our array.

`$videodata = array_filter($videodata);`

Perfect! Now we have an array of all out video’s, without any empty results. Let’s output our videos. I have two video’s so: 
`echo($videodata[0].‘ ’); echo($videodata[1]); `

And repeat for every new video.. ! I can see you thinking “WHAT!? AM I SUPPOSED TO CHANGE THE CODE WITH EVERY NEW VIDEO!?”

No, don’t worry, there is an easier way in PHP to do this called Loops.

```
foreach($videodata as $video) {
    echo($video.‘ ’);
}
```

In PHP and many other languages loops are a very powerful construct. With loops you don’t have to repeat yourself and your code can be more adaptive and dynamic and automatically output things when a new video appears *phiew*. With the foreach loop we are saying “for each videodata, call the element `$video` and then echo it, and add a space”. It outputs the same code as earlier, but without the hassle. Great! There are some different loops in PHP, the foreach is a shortcut and very often used to iterate through arrays. If you want to know the key of the array as well, for instance in the example of fruits earlier you can specify it as such: 

````
foreach($fruits as $nameOfFruit => $fruit) {
    echo($nameOfFruit);
}
```

You can also use the “for” loop to have the same result, but by counting. This is useful if you need to know which iteration you are on, let’s say we want to output only the first eleven video’s, there are some ways to do this in PHP. With a for loop: 

```
for ($videosCount = 0; $videosCount <= 10; $videosCount++) {
   echo $videodata[$videosCount];
}
```

Now you are specifying your own variable $videosCount, say it should be 0, and as long as videosCount <= (less or equal to 10) it should keep echo’ing, and then when it’s done, it should add one to the count. So it will go through this 11 times, each time looking for 0 - 10 in the `$videodata`, so if one of the numbers is not set, like now - I only have two video’s, it will give us an error. We can use the if clause again, to check if the data is set. 

```
if(isset($videodata[$videosCount])) {
   echo $videodata[$videosCount];  
}
```

Now it will output video 0 - 10, but only if the video with that index exists in the array we earlier created. In PHP there is also a “while” loop, which keeps looping while a set condition is true. “while($weStillHaveBananas) {‘eat a banana’}”. This is where a common programmers joke comes from because it is easy to create so called “endless loops” with while conditions that never become false. 

“Why did the programmer get stuck in the shower for hours?”
“Because on the bottle it said lather, rinse, repeat!”

You can read more detailed information about loops in the PHP documentation: 
http://php.net/manual/en/control-structures.foreach.php
http://php.net/manual/en/control-structures.for.php
http://php.net/manual/en/control-structures.while.php

Our video links doesn’t look very nice, so let’s end this chapter by introducing an alternative syntax to PHP control structures (foreach, if, for, etc.) to make it easier to mix HTML and PHP. 

```
<?php foreach($videodata as $video): ?>
   <div>
       <a href="<?php echo $video; ?>"><?php echo $video; ?></a>
   </div>
<?php endforeach; ?>
```

Now we have all the video links nicely clickable! Neat. To show them as videos we would need to use iFrames. This is something that you can read more about on your own and we leave it as an exercise to the user. Now we store and output video links, how cool is that? Let’s commit our code before moving on.
<commit code>

Our code is now doing something useful. We are storing links to video’s and outputting them. But how about we store them in one place, and output them in another page? This way we are creating an admin area on our website. Let’s do that! 

Start by creating a new folder and call it “admin”. This is where we will have all of our admin code. In this folder you can create a file called “AddVideos.php” this is where our form will be. Let’s copy paste the code from Course.php into this file and remove the part where we output the video’s, as we do not need it. <remove code> and then change the location of the form to go to this file <change to AddVideos.php in the action>. In Course.php, remove the form and the styling. We only want to output the video’s here. In AddVideos.php we should also ensure that the videos.txt is one folder back, so it is in the main folder! The way to do that in the linux world is with “../” syntax it means “one folder back” let’s change that. 

`file_put_contents('../videos.txt', $_POST['youtube-link'] . ',', FILE_APPEND);`

Every website has a landing page, one where the user comes to and know where to go, let’s make this our Course page. Rename the “Course.php” page to “Index.php”. We will have another landing page later, where we may rename this one back. “Index.php” is a filename that the PHP server recognises as “This is where I start!” 

So we have a landing page of our “regular” site, we also need a landing page if we go to /admin/ let’s make this our AddVideos.php file that we just created, rename it to Index.php. Also change the “action” in the form to “Index.php”

Let’s see what happens now if we start our webserver from the root directory and then browse our website. 

`php -S localhost:8080`

We see the video links! And if we go to localhost:8080/admin/ we see the admin page without having to write /Index.php, because if we do not specify a file, that’s where PHP will look. We can also go to localhost:8080/admin/Index.php and have the same effect. 

The website still doesn’t look quite like a website though. Let’s add a menu so we can jump between the pages that we have. In HTML we can use the <nav> element for this. Then we use <ul> which means unordered list, and <li> which means a list item, for each item in the menu. Let’s copy paste it to the other file as well. 

``` 
<nav class="menu">
   <ul>
       <li><a href="/Index.php">Course</a></li>
       <li><a href="/admin/Index.php">Admin</a></li>
   </ul>
</nav>
```

Let’s also add a title to the admin page: 
`<h1>Admin: Add Video's</h1>`

Now we can easily jump between. Much better! 

## 6: Functions: Structuring the PHP logic
So far we have written the PHP functions directly in between the HTML markup. It becomes a bit harder to read the HTML that way with so much logic in between. It is much nicer if we can make our own functions, just like we have been using the PHP built in ones to define our logic and have it in one space. So, let’s do that for outputting video’s! Let’s go to Index.php, where we have our video’s listed. We see that there is some logic here, let’s move that someplace else so that we have mostly HTML here, and PHP someplace else, then this file becomes much easier to change without risking breaking the logic. We can also use these functions on other places if we want to list the video’s there for instance! Let’s create a file called “VideoFunctions.php”. In there we can create out first function. A function is created using the keyword “function” and then after we have the function name, followed by any parameters in the parenthesis, and like we saw before: The logic itself between the curly braces. The syntax of PHP is quite consistent. 

```
function getVideoData()
{
          
}
```

Now we can take the code from Index.php and put it inside this function. Let’s first make a function to get the video data. 

```
function getVideoData()
{
   $videotext= file_get_contents('videos.txt');
   $videodata = explode(',', $videotext);

   $videodata = array_filter($videodata);
}
```

We need to tell the function that “When I am done, I want to give whoever calls me, this data” it does that by using the “return” keyword. So instead of $videodata = we return that data with: 

`return array_filter($videodata);`

“Give whoever calls me the result of array_filter as an answer to their call!” 

If we go back to Index.php we need to tell the file that we want to use the VideoFunctions.php file. 

`<?php include 'VideoFunctions.php' ?>`

Then we replace the $videoData logic with: 
`<?php $videodata = getVideoData(); ?>`

The code works just like before but we have abstracted away the logic to another place! This is much easier for a non PHP programmer to work with. 

## Chapter 5: Templating; Do not repeat yourself
### Chapter description

Up to now we had a lot of repetition. It wastes time to change code in many places. We will show you a way that is commonly used to avoid repetition called “templating”, so that we can change our code in only one place when something changes. 

## Chapter 6: Object Oriented Programming
### Chapter description
Learn a programming concept used in PHP and many other languages to help us as humans understand our code better.

## Chapter 7: Storage Solutions
### Chapter description
Using files for storage works for a lot, but at some point you will come across limitations, like we already have in chapter 5. We will introduce you to a better way to store more complex data. 

## Chapter 8: User registration
### Chapter description
We will use GitHub to be able to login and save user specific information on our website. 

## Chapter 9: Staring the videos
### Chapter description
Since we have user registration since chapter 8, we are using it here to let users individually star videos they might want to refer to later. 

## Chapter 10: Personalising your site
### Chapter description
Your site is done, but does it feel like you? Introducing you to some things you can do to change the look and feel. 

## Chapter 11: Where do I go next?
### Chapter description
Congratulations, you can now create a simple PHP website. But there is still a lot to learn, we have some ideas and resources for you. 
