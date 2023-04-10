#steps for my Ip Depolyment using jenkins.

// Step One
Forked the repo and cloned it to my local machine.

// Step Two
Created an account in mongodb cloud platform and created my first cluster by the name gallerycluster. Then inside the cluster, i created three databases namely, darkroom, darkroom-dev, and darkroom-test.
Also i updated the _config.js file with my db username and password.

//Step Three
Created a pipeline GP-Final
Configured my git webhook and jenkins to trigger builds automatically after a git push request.

//Step Four
Created a heroku app for my project's production environment.

//Step five
updtaed my pipeline to install dependancies needed clone the project from git, build the project by running npm install since its a nodejs app. confirgured my connection to the mongodb cloud database and finally deploy it to heroku.

//Step Six
Deployed to heroku and was able to access the website. I Also updated the website to read MILESTONE 2.

//Step six 
Configured my test manager "mocha" to test and exit by adding an exit flag. Also configured an email notification for a successful build and test. Added Milestone 3

//step seven
Configured Slack to notify me and the Team manager of successfull deployments to heroku. Added Milestone 4 to the landing page.


//Step Eight
Add my jenkins file to my remote and local repository


