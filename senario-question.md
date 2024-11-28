
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
