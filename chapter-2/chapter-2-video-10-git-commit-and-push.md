# Chapter 2 video 10: Commit and push, the git workflow
Now you have a repository, and you know how to run your code locally. Your code is only on your machine. If you go to github and browse your repository, nothing is there yet.

A common workflow that programmers use is the following: 
- Write your code.
- Add your code to git. 
- Commit the code in git, aka make a new version with a clear message.
- Push the code to the remote repository, aka put the code online and ensure it's not only on your machine. 

Now let's go into how to implement this workflow step by step. Open your terminal. Write "git status" this will show you a status of how your files are right now. Like on my screen you will see a list of untracked files. This means that you have files that are not yet in the git version control. It's time to add them. Write "git add (index.php the filename of the file we created earlier)". Now write "git status" again and you will see your file with a new status. It will say "new file". With add it is not a new version yet. So there's no commit yet! This is a very common thing to forget. So now we need to commit it. Write "git commit -m 'My first commit'" it will say "1 file changed". So now we created a new commit and git recorded the actual content of the file in a new version. You can see all your versions by writing "git log -n 5". The n stands for how many versions you want to see. 

Now it's time to put your code and version history to github! Write "git push" to push it to your remote. Now go to your github repository and you will see your changes there. This workflow will often take some time getting used to, so don't worry if it seems like a lot now. It gets easier as we go!