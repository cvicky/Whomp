This is my second day trying to figure out git.

I added this on the online repository to see if I could see this on my local repository.

This website/blog was super useful: http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1

DAY 3, 5/7/15 UPDATE: I cannot. lol
But I figured out why not. 
(This was a super useful youtube video: https://www.youtube.com/watch?v=0fKg7e37bQE
"Github Tutorial For Beginners - Github Basics for Mac or Windows & Source Control Basics" user handle: LearnCode.academy)

NOTE TO SELF: Any time you make changes on the online repo, you need to pull the changes from it by using the command 
>>git pull "https//: link from the clone link at the bottom right of the page"

So, these are the list of commands that I know so far. I will probably make a master list later
>>git config --global user.name "name name"
to link the git file with your name

>>git config --global user.email "email@email.com"
to link the git file with your email

===================================
not sure if you need to type these config commands every time you open a repo that you have already linked with the master branch, but i'll figure it out soon enough
===================================

>>mkdir directory
to make a new repo directory

>>touch file.txt
to create a new file

>>cat filename
to open a file

>>git add filename
to tell git you want to add a file to your online rep, gets it ready to be committed

>>git status
tells you what changes have been made and haven't been committed to the online repo yet

>>git add -A
to tell git you want to add everything you made changes to instead of adding individual files, cuz that's slow and annoying

>>git commit -m "I made changes"
it's a message saying what you want to commit to git, -m indicates a message "this part is a string message"

***
>>git commit
takes you to a window where you can write a full blown multi-line message instead of just a few words,
to exit this, write your long message and type >>:wq 

>>:wq
I imagine this means "want quit", idkk, but it gets you out of a full message commit window and back to command line termnial
***

>>git push
to push into git what you commited, this is the point where you can refresh your online repo and all the changes will appear updated in your repo, yay

>>git pull
this is what you type into the command line on your computer in order to pull any updated changes from your online repo and make them appear in your local repo, do this to sync up the online and local repos


****so do git status, git add -A, git commit -m "message", git push, git pull every so often so things don't get out of whack and fall behind, sync em up!




