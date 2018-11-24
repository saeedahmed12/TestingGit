This directory was created on 10.30.18 for me to learn how to use github and git.

I am using this video for guidance:
https://www.youtube.com/watch?v=9xePqfHP7k8


There is a github repository that goes along with the video to be found here:
https://github.com/mjhea0/thinkful-mentor/blob/master/git-workflow.md

If changes made remotely, then this worked (but need to be careful) to bring back in to local:
git pull https://github.com/saeedahmed12/TestingGit.git

How to use with VS studio Code:
https://lh3.googleusercontent.com/BUqno_MU9v4mxOqYhD1i2xeYvjkm3chuE7FVbkhmBD6OiiJ2Y7fNpYydbSAQhI05f1CFjXwyWOQwHCZD8zw8EW-LKd37llKnROjZYGpV3GCs70-TmPSkYcsG9nV0nUFu2rnWdWwcXVW2AAJDgP3jgGQ9quUg4HoHHBSAsGKjQZ5MZ7_nq3nDPVD0iF8JohlJfFYe2kqv0Eg0G7_o9ZF_IrGi8EvEX25qungbR9CRgyEyDPUECR2bnt9OuwTfhRgWpP2AdsBfGOKToi6HKoMi9q-_TFD9yI0gthrlNu47S4JSi11t6cX3mCYfjjWMMXcxTM6VmSMmJcwyG_MTmvyIIrSyINVuHKlXz06Kq7ocMhfSYdPZ6b7GjLb9xrl6zHKsJoxrq5siBWs-GLyYmZTrXfqHNKhx5Knwocdj8AHMXlQb5onQuV-CvhfbuIBPKwfYbgTywyyoFr2wPCXejmVnDsYRkSozxR_chRRAEKJ5Ih1_0tE8iAtaIZK1EU43wEhwyp1X2bP7DS2jLm5NwEGbQCX-CvSRynDaFdW8LDulvcoPTLnr7JQQUPF10Of0jAaZ6UIYgvHRB_dbcr7JcT_A-sKsibEuyOYFfWZH4I2_VaBB5loP-ohwdPnqLMMs-Lc7B9LBUY0IEBswF52YpTZGv8j9=w734-h978-no


How to use with Atom:
(see this video:https://www.youtube.com/watch?v=TzKi6ZZtIAo)
(core packages 'github' and 'gitdiff')

1. First put a 'git' in folder of interest:

  a. in command palette in Atom, type 'git clone'
  
  b. enter the respository's url
  
  c. enter local folder path
  
  d. folder on local drive where repo is cloned to must be empty to start
  
  e. the first file that is in the repo should be created remotely and this is automatically pulled when the remote repo is cloned
  
  f. after that other files can be pushed

2. 'Toggle Git Tab'

3.  Stage, commit, push


How to use in sublime text 3, using (sublime git)
(see tutorial here   https://sublimegit.readthedocs.io/en/latest/tutorial.html#sharing-our-project-with-the-world)


If git already in place in local folder (this worked even though the local repo had been set up in atom)
1. In command palette (ctrl-shift-p) type 'git s' to open status
2. In status type 's' for stage, 'c' for commit (there is also a git: quick commit command)
3. If remote repository has been set up, then use git push (or in some cases git push current branch)

if git has not been set up locally, then follow instructions in tutorial to set it up, or use the process above in Atom.


Commands using unix interface:

  225  cd "C:\Users\Ahmed\OneDrive\Documents\for online content\forProgmWebsites\github"
  226  ls
  227  git status
  228  git config --get remote.origin.url
  229  git add
  230  git status
  231  git add -A
  232  git commit -m "new"
  233  git push


