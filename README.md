 GitHub Actions Deployment
 Setup Process
1. Created `.github/workflows/deploy.yml` file
2. Configured GitHub Pages to use GitHub Actions as the deployment source
3. Workflow triggers automatically on push to main branch

 Two Options to Trigger Depployment
 Automatic: Push changes to the default branch
 Manual: Go to Actions tab > Click "Deploy static content to Pages" > Click "Run workflow"

 Deployment Details
 The workflow automatically runs on every push
 It uploads the repository contents to GitHub Pages
 The site is accessible at: https://kevinpiper125.github.io/my-dvops-website/
 

 I tested this out by adding things to the README and pushing it to the main branch


 (Last Assignment)
Kevin Piper
Demonstration of deploying website to gihub pages

This is a working repository for my Introduction to DevOps Class.  This repository was to showcase my understanding of git and github.

Steps I did to set up git for this assignment

1. I initialized  the git repo using "git init"
2. I made sure Git was configured with my username and email (it of course was from previous classes)
3. To start the commit process I added the files using "git add . "
4. I created the initial commit using the `git commit -m "Initial Website Commit" `
5. I created the repository that would be recieving these files
6. I linked the created git repo with my assignment using `git remote add origin git@github.com:KevinPiper125/my-dvops-website.git`
7. I pushed the code to the repo using `git push -u origin main`
8. I enabled the github pages in the repo settings


Challenges
I had a bit of trouble due to the name being my-dvops-website  I kept adding an "e" as in devOps and I thought the site was broken.  Just a spelling error though. Probably not the best name choice.

But it did function and here is the site https://kevinpiper125.github.io/my-dvops-website/
