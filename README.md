# BoilerPlate Template to Start off FEE projects
This is a simple setup to start off any front end project. <br>

<strong style="color: blue;">Areas setup in this Project:</strong><br>
  1. It creates a dummy directory structure for your CSS and JS
  2. It creates a grunt.js file to run the important task needed to run a front end project.<br>
      a. Sets your Sass, converts to CSS and then mimifies it.<br>
      b. Sets your JS through Uglify, combines all your js files and mimifies them.<br>
      c. It relaunches your browser any time it detects a change with browserSync<br>
      d. Package.json sets all calls to all the tasks needed to run this project.<br>
      
      
<strong style="color: blue;">Steps to use this project:</strong><br>
1. Create a directory in your computer of where you want to house this project.
2. In GitHub under the repository name, click Clone or download.
3. In the Clone with HTTPs section, click  to copy the clone URL for the repository. 
4. Open Terminal windows -> cmd -> traverse to directory you created.
5. Type git clone, and then paste the URL you copied in Step 2.
   ------ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY

6. Once Clone is succesful -> Run "NPM Install"
7. Run command line  npm start
8. &nbsp;If you get <strong>errors</strong> requesting you to install Ruby you may need to go: http://sass-lang.com/install.<br>
        ----&nbsp;Follow instruction on how to install ruby and sass.<br>
        ----&nbsp; Reason for this is you need Ruby and Sass install at the global level to have this run.<br>
9. If you now have ruby installed and you get the following error: 
Warning: You need to have Ruby and Sass installed and in your PATH for
this task to work. More info:
https://github.com/gruntjs/grunt-contrib-sass Use --force 
to continue.   RUN the follow command:  gem install sass  

10. Magincally your browser should come up at  http://localhost:3000/<br><br>
11. Now open your project in your favorite IDE<br><br>
12. Make a small change, save and see them happen on the browser.


**********************************************************************
Reminders of Commit Commands to any project:
1. If this is a new project dont forget to "git init" first
2. Git status - shows you all files that were changed.
3. Git add .  - adds the files to local repo
4. git commit -m "my changes"  - commits your changes to local repo
5. git push origin master   - pushes them out to Github the origin.


     <br>
 Happy Coding!!
