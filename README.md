## Git Cheat Sheet

<img src="https://s3.amazonaws.com/after-school-assets/cheating.gif" width="300" align="right" hspace="10">

Git got you freaked? It's normal. There are a lot of commands that have control over a lot of different actions. This is precisely why we never expect you to memorize anything. In fact, we're even providing you with a cheat sheet. It's not cheating when it's programming!

## Creating A New Project From Scratch:

1. Once you've created a directory that you want to track, initialize git with `git init`. Make sure your directory contains a README.md file.

2. To set up your github.com directory:
  + Go to your profile on github.com.
  + Click on the + button on the top right of the page. Choose 'new repository'
  + Give your new repository the same name as your local project directory.
  + In your terminal, add the github repository as 'origin.' You should be able to copy this from the github page once you've save it: `git remote add origin git@github.com:dfenjves/repository-name.git`
  

### To Push Work To GitHub: 
1. Check the status of your project with `git status` 

2. When you're working on a project and want to commit your code:
  +  Use `git add` with the filename you want to to add to your 'holding station'
  + When you're ready to commit, `git commit -m "add a message about the changes you've made`
  + When you're ready to push to your repository on github.com: `git push origin [branch name]` (if it's the first time you do this, add the flag `-u` after `git push`)
  
### To Create A New Branch:
1. To create and switch to a new branch use `git checkout -b [branch_name]`

2. To switch to an existing branch use `git checkout [branch_name]`

### To Merge A Branch Into Master:
1. `git checkout master` to switch into your master branch
2. `git merge [other-branch]`
3. (optional) push to github using `git push`
  
### To Copy An Existing Repository To Your Computer:
1. Go to the repository page on github.com
2. Click on the fork button on the top right of the screen.
3. Copy the SSH clone link on the right side of the new page.
4. Navigate to the development folder in your terminal and type `git clone [copied_text]`
5. cd into the folder you downloaded on your computer.
<p data-visibility='hidden'>View <a href='https://learn.co/lessons/hs-git-cheat-sheet' title='Git Cheat Sheet'>Git Cheat Sheet</a> on Learn.co and start learning to code for free.</p>
