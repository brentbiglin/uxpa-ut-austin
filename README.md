# UXPA UT Austin

## How to Submit a Blog Post to UXPA UT Austin

1. Create a GitHub account and log in.
2. At the top right of this page, click "Fork."
3. You will now have your own copy (or fork) of the UXPA UT Austin repository in your GitHub account.
4. In your own repository, click the green "Clone or download" button to copy the repository from your GitHub account online to your computer. The easiest way to do this is to "Open in Desktop." If you haven't already downloaded and installed the GitHub Desktop app, this will prompt you to do so.
5. You should then have a copy of the site on your computer, which you can change.

To host the site locally to make changes and view changes:
1. Open Terminal
2. Go to the uxpa-ut-austin folder (remember that the command ```ls``` allows you to view the contents of the folder you're in, ```cd FOLDER``` takes you to that folder, and ```cd ..``` with two periods navigates to the parent folder of the one you're in).
3. Run the command ```hugo server```. This builds the website on your computer and hosts it locally on your computer.
4. Go to http://localhost:1313/ in your browser
5. Any changes you make will be updated automatically.

To push a change that you've made to GitHub:
1. In the uxpa-ut-austin folder
2. ```git status```
3. ```git add THE-FILE-YOU-CHANGED-OR-ADDED```
4. ```git commit -m "THE CHANGE YOU MADE"```
5. ```git push```
6. This will have updated your own personal fork of the repository. To request that your change or update is pushed to the UXPA UT Austin website, go to your repository's page on the GitHub website and click "New pull request."
