
### You have a Java web application codebase hosted on GitHub. How would you set up a Jenkins job to build and deploy this application automatically whenever changes are pushed to the master branch?

Step 1: Create a Jenkins Job.
Step 2: Configure GitHub Hook Trigger.
Step 3: Create a GitHub Repository.
Step 4: Connect a GitHub Repository.
Step 5: Adding a WebHook in GitHub.
Step 6: Manually Building Jenkins Job.
Step 7: Trigger Build with GitHub Commit. Summary.

OR

1. Open Jenkins dashboard. Click on manage jenkins

2. Click on Configure system and under github configuration click advanced tab.

3. Check 'Specify another hook url' for GitHub configuration. 

4. Now you will get a url in the textbox. Copy this url as it is required in the next steps.

5. Now open your github repository. Go to settings -> webhooks -> add webhooks.

6. Now paste the url from step 4 in the payload url section. Next click on just push the event Now you should be able to see the added webhook in the list of webhooks.

7. Now go to jenkins dashboard. Go to your project configuration. In the build triggers section select github hook trigger for git scm polling. Save the changes.

### You notice that your Jenkins server is running slow, and jobs are taking longer to execute. How would you diagnose and resolve performance issues in Jenkins?

1.Review the Jenkins logs (/var/log/jenkins/jenkins.log) for errors, warnings, or long execution times for specific operations.

2. Inspect the number of executor slots and queued jobs. If there are too many jobs running simultaneously, it can strain the system. Ensure the JAVA_OPTS or JVM settings are optimized for the server's available resources.

3. Disable unused plugins as some may consume significant resources. Update plugins to the latest versions since old versions might have performance bug.

4. If you use an external database (e.g., MySQL), check its performance and query execution times. Ensure the database is adequately sized and indexed.

5. Storage Issues:
Inspect the disk usage of Jenkins, particularly in directories like $JENKINS_HOME/workspace and $JENKINS_HOME/jobs.
Check if the disk is running out of space or is heavily fragmented.