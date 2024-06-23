# This Read Me Contains details of the steps I took to complete the assignment"

1. Cloning a Repository:
    - I chose the repository for a html and css project at https://github.com/jonasschmedtmann/html-css-course
    - I cloned this repository to my local machine on git bash terminal by using the command: git clone https://github.com/jonasschmedtmann/html-css-course
    - I explored the repository's structure, files, and history.

2. Forking a Repository:
    - I also forked the repoitory to my GitHub account 
    - Then I cloned the forked repository to my local machine on git bash terminal by using the command: git clone https://github.com/barbzyqueen/html-css-course.git
    

3. Creating and Switching Branches:
    - In the git bash terminal, I created a new branch and switched to it by using the command: git checkout -b feature-update

4. Making Changes and Committing:

    - In the feature-update branch, I created a index.html file
    - Then I added the changes to the staging area using the command: git add .
    - I commited the changes using the command git add -m "Added Changes to index.html file in feature-update branch"

5. Merging Changes:
    - I switched back to the master branch using the command: git checkout -
    - I merged the changes from the `feature-update` branch into the master branch using the command: git merge feature-update
    - The index.html file was added to the master branch


6. Creating Conflicts:
In my forked repository on my local machine I also created an index.html file
    - I created an index.html file
    - Then I added the changes to the staging area using the command: git add .
    - I commited the changes using the command git add -m "Added  index.html file in master branch"
    - In the git bash terminal, I created a new branch and switched to it by using the command: git checkout -b feature-update
    - In my the feature-update branch I modified a line of code. I changed the contents of the h2 tag in lind 9
    - I added and committed the changes 
    - I switched back to the master branch using the command: git checkout -
    - I modified the code on line 9 again in the index.html file of the master branch
    - I added and committed the changes using the command git: merge feature-update
    








Task 2: Managing Branches

3. Creating and Switching Branches:

  - In your local repository, create a new branch (e.g., `feature-update`).

  - Switch to the newly created branch.



4. Making Changes and Committing:

  - Make changes to a file or add a new file.

  - Commit the changes to the branch.



5. Merging Changes:

  - Switch back to the main branch.

  - Merge the changes from the `feature-update` branch into the main branch.



Task 3: Handling Conflicts

6. Creating Conflicts:

  - In your forked repository, make changes to the same file that you modified in Task 4.

  - Commit the changes.



7. Resolving Conflicts:

  - Create a new branch to resolve the conflict.

  - Resolve the conflict manually in the file.

  - Commit the changes and merge the branch back into `main`.



Task 4: GitHub Pages

8. Enabling GitHub Pages:

  - In your forked repository, create a simple HTML file (e.g., `index.html`).

  - Enable GitHub Pages for the repository and set the source branch to `main`.



9. Accessing the Published Page:

  - Visit the GitHub Pages URL for your repository and verify that the HTML file is accessible online.



Task 5: Open Source Exploration

10. Exploring Open Source Projects:

  - Search for an open-source project on GitHub related to your interests.

  - Explore the project's documentation, issues, and contribution guidelines.



11. Opening an Issue:

  - Open a new issue in the chosen open-source project, suggesting an improvement, reporting a bug, or asking for clarification.










This repo contains starter files and final code for all sections and projects contained in the course.

Use starter code to start each section, and **final code to compare it with your own code whenever something doesn't work**!

👇 **_Please read the following Frequently Asked Questions (FAQ) carefully before starting the course_** 👇

## FAQ

### Q1: How do I download the files?

**A:** If you're new to GitHub and just want to download the entire code, hit the green button saying "Code", and then choose the "Download ZIP" option. If you can't see the button (on mobile), use [this link](https://github.com/jonasschmedtmann/html-css-course/archive/master.zip) instead.

### Q2: I'm stuck! Where do I get help?

**A:** Have you actually tried to fix the problem on your own? Have you compared your code to the final code? If you failed fixing your problem, please **post a detailed description of the problem to the Q&A area of that video over at Udemy**, along with a [codepen](https://codepen.io/pen/) containing your code. You will get help there.

### Q3: What VSCode theme are you using? What about extensions and settings?

**A:** I use [One Monokai](https://marketplace.visualstudio.com/items?itemName=azemoh.one-monokai) in this course. [Here is the complete VS Code setup for this course](vscode-setup.md).

### Q4: Can I see the final version of the Omnifood project?

**A:** Sure! Here you go: [Omnifood](https://www.omnifood.dev).

### Q5: Where can I find the coding challenge solutions?

**A:** They are all on codepen, in [this collection](https://codepen.io/collection/7b5e288cb64df1ecc5da8d7a0e78c007?grid_type=list).

### Q6: Where is the resources page you keep mentioning?

**A:** It's on my website at <https://codingheroes.io/resources>. You can subscribe for updates 😉

### Q7: Videos don't load, can you fix it?

**A:** Unfortunately, there is nothing I can do about it. The course is hosted on Udemy, and sometimes they have technical issues like this. Please just come back a bit later or [contact their support team](https://support.udemy.com/hc/en-us).

### Q8: Videos are blurred / have low quality, can you fix it?

**A:** Please open video settings and change the quality from 'Auto' to another value, for example 720p. If that doesn't help, please [contact the Udemy support team](https://support.udemy.com/hc/en-us).

### Q9: I want to put these projects in my portfolio. Is that allowed?

**A:** Absolutely! Just make sure you actually built them yourself by following the course, and that you understand what you did. What is **not allowed** is that you create your own course/videos/articles based on this course's content!

### Q10: I love your courses and want to get updates on new courses. How?

**A:** First, you can subscribe to my email list [at my website](http://codingheroes.io/resources). Plus, I make important announcements on twitter [@jonasschmedtman](https://twitter.com/jonasschmedtman), so you should definitely follow me there 🔥

### Q11: How do I get my certificate of completion?

**A:** A certificate of completion is provided by Udemy after you complete 100% of the course. After completing the course, just click on the "Your progress" indicator in the top right-hand corner of the course page. If you want to change your name on the certificate, please [contact the Udemy support team](https://support.udemy.com/hc/en-us).

### Q12: Can you add subtitles in my language?

**A:** No. I provide professional English captions, but Udemy is responsible for subtitles in all other languages (automatic translations). So please [contact the Udemy support team](https://support.udemy.com/hc/en-us) to request your own language.

### Q13: Do you accept pull requests?

**A:** No, for the simple reason that I want this repository to contain the _exact_ same code that is shown in the videos. However, please feel free to add an issue if you found one.
