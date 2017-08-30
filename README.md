## How to Submit a Blog Post to UXPA UT Austin

1. Create a GitHub account and log in.
2. At the top right of this page, click "Fork."
3. You will now have your own copy (or fork) of the UXPA UT Austin repository in your GitHub account.
4. On the page of your fork of the repository, click the green "Clone or download" button to copy the fork from your GitHub account online to your computer. The easiest way to do this is to "Open in Desktop." If you haven't already downloaded and installed the GitHub Desktop app, this will prompt you to do so.
5. You should then have a copy of the site on your computer, which you can change.

### To host the site locally to make changes and view changes:
1. Open a terminal.
2. Go to the uxpa-ut-austin folder that you now have on your computer (remember that the command ```ls``` allows you to view the contents of the folder you're in, ```cd FOLDER``` takes you to that folder, and ```cd ..``` with two periods navigates to the parent folder of the one you're in).
3. Run the command ```hugo server```. This builds the website on your computer and hosts it locally on your computer.
4. Go to http://localhost:1313/ in your browser
5. Any changes you make will be updated automatically.

### To make a new blog entry:
1. Open a terminal and go to the uxpa-ut-austin folder.
2. Type the command ```hugo new post/YEAR-MONTH-DAY-YOUR-NAME.md```. For example, if Han Solo created a new blog post on May 25th, 1977, he would type: ```hugo new post/1977-05-25-han-solo.md```.
3. Open the file that you've created in a text editor of your choice (Vim, Atom, Sublime, Notepad, etc.).
4. This is a Markdown file. The content in between the dashes is called the front matter, and provides information about the site. You'll want to change the "title" to whatever you want the title of your blog post to be.
5. Type your post in the Markdown language below the front matter. See [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) for a Markdown Cheatsheet. Your post will be edited for format before it's published, so don't worry about it too much! Just type your text into the file.
6. Check http://localhost:1313/ to see your changes in realtime.

### To push a change that you've made to GitHub:
1. Navigate to the uxpa-ut-austin folder on your computer in the terminal.
2. ```git status```
3. ```git add THE-FILE-YOU-CHANGED-OR-ADDED```
4. ```git commit -m "blog entry from YOUR NAME"```
5. ```git push```
6. This will have updated your own personal fork of the repository. To request that your change or update is pushed to the UXPA UT Austin website (the original repository), go to your fork's page on the GitHub website and click "New pull request."
7. After being reviewed, your pull request will be accepted and your blog post will be published to the site!
