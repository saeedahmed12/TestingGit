This directory was created on 10.30.18 for me to learn how to use github and git.

I am using this video for guidance:
https://www.youtube.com/watch?v=9xePqfHP7k8


There is a github repository that goes along with the video to be found here:
https://github.com/mjhea0/thinkful-mentor/blob/master/git-workflow.md

If changes made remotely, then this worked (but need to be careful) to bring back in to local:
git pull https://github.com/saeedahmed12/TestingGit.git


How to use with Atom:
(see this video:https://www.youtube.com/watch?v=TzKi6ZZtIAo)
(core packages 'github' and 'gitdiff')
1.  First put a 'git' in folder of interest:
-in command palette in Atom, type 'git clone'
-enter the respository's url
-enter local folder path
-folder on local drive where repo is cloned to must be empty to start
-the first file that is in the repo should be created remotely and this is automatically pulled when the remote repo is cloned
-after that other files can be pushed

2. 'Toggle Git Tab'

3.  Stage, commit, push


How to use in sublime text 3, using (sublime git)
(see tutorial here   https://sublimegit.readthedocs.io/en/latest/tutorial.html#sharing-our-project-with-the-world)


If git already in place in local folder (this worked even though the local repo had been set up in atom)
1. In command palette (ctrl-shift-p) type 'git s' to open status
2. In status type 's' for stage, 'c' for commit (there is also a git: quick commit command)
3. If remote repository has been set up, then use git push (or in some cases git push current branch)

if git has not been set up locally, then follow instructions in tutorial to set it up, or use the process above in Atom.
