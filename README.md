[![Open Source Love](https://firstcontributions.github.io/open-source-badges/badges/open-source-v1/open-source.svg)](https://github.com/firstcontributions/open-source-badges)

<h1>Make your first Pull Request. !</h1>
<p> A repository to help you start your open source journey! 💫 </p>
<h2> ❓ What To Do </h2>
<ul><li>Add your name in the <code>Contributors.md</code> file to make your first pull request 🚀</li></ul>

How to make a Pull Request
If you think that you can add a new feature or want to fix a bug. You can start contributing by following the below instructions:

## Create a folder at your desired location (usually at your desktop).

<ul><li>Open Git Bash Here</li></ul>

<ul><li>Create a Git repository</li></ul>

<ul><li>Run command</li></ul>

     git init
     
<ul><li>Fork the repository</li></ul>
<ul><li>Clone your forked repository of the project</li></ul>

     git clone https://github.com/<your_username>/repository_name.git
     
<ul><li>Navigate to the project directory</li></ul>
<ul><li>Add a reference(remote) to the original repository</li></ul>

     git remote add upstream https://github.com/repository_owner/repository_name.git
     
<ul><li>Check the remotes for this repository</li></ul>

      git remote -v
     
<ul><li>Always take a pull from the upstream repository to your main branch to keep it updated as per the main project repository</li></ul>

     git pull upstream main
     
<ul><li>Create a new branch (prefer a branch name that relates to your assigned issue</li></ul>
     
     git checkout -b <YOUR_BRANCH_NAME>
     
   <ul><li>Perform your desired changes to the code base </li></ul>
   
   
   
  ### Check your changes
     git status
     git diff
  ### Stage your changes
     git add . <\files_that_you_made_changes>
  ### Commit your changes.
     git commit -m "relavant message"
  ### Push the committed changes in your feature branch to your remote repository
     git push -u origin <your_branch_name>
     
  ### To create a pull request, click on <code>compare and pull requests</code>
  ### Add an appropriate title and description to your PR explaining your changes.
  ### Click on <code>Create pull request</code>
  
 ## This project is open for contributions! (under [Hacktoberfest 2022](https://hacktoberfest.digitalocean.com/))
We welcome any and all contributions that add value to this project.
If you're facing an issue when trying to self-host this or setting up this project or experience a bug, feel free to [open an issue]

 Congratulations🎉, you have made a PR to the repository. Wait for your submission to be accepted and your PR to be merged by a maintainer.
Show some ❤️ by starring this repository and do follow me for more updates✨
