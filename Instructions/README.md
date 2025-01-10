# Github Classroom and IntelliJ

Please follow the directions below EXACTLY to complete this recitation successfully.

1. If you do not have a GitHub account, head over to https://github.com and sign up for an account.  <p/>
2. If you have not install IntelliJ, go to <a href="https://www.jetbrains.com/idea/download/">IntelliJ Download </a> and download and install the IntelliJ IDE Community Edition.  This is the free version of the IDE.<p/>
3. Click on <a href="http://github.com">GitHub Repo</a>. Click on the <span style="color:white; background-color:green;">Use this template</span> button.  This will make a copy of your instructor's repo on your account.
4. You should now see your repository with a green Code button on the top right as shown in the image below.<p><image src="./xstep4.png" height="300"></p>
5. You will now need to create a Github authentication token to be used in IntelliJ.  Click on your avatar on the top right of the screen.  You should see a drop-down menu as shown in the image below.   Select  Settings. <p/><image src="./xstep5.png" height="300"></p>
6. On the Settings page, click on the Developer Setting menu item on the left as shown below.<p/><image src="./xstep5.png" height="300"></p>
7. Select the **Personal Access Tokens** as shown in the image below.  Make sure to select **Tokens (Classic)**.<p/><image src="./xstep7.png"></p>
8. Click on **Generate new token** button and again select the classic option.
9. Enter **General Access** in the Note textbox and select the repo, workflow, gist, and read:org checkboxes as shown in the image below. Also, for the expiration, select custom and enter May 31, 2023.  This will make your token valid for the entire semester.<p/><image src="./xstep9.png"></p><p><image src="./xstep9-2.png" width="430px"style="margin-left:115px;"></p>
10. Click the green <span style="background-color:green; color:white;">Generate Token</span> button at the bottom of the screen.
11. Copy the token by clicking on the copy button as indicated in the image below.  You should store the token somewhere because you will not be able to recover it.  If you should forget it, you will need to regenerate a new token.<p/><image src="./step11.png"></p>
12. Now, open up IntelliJ and click on Customize and then All Settings as shown in the  image below.<p/><image src="./xstep12.png" height="300"></p>
13. Expand the Version Control item on the left of the window and select Github.  Then click on the + as shown in the image below.<p/><image src="./xstep13.png" height="300"></p>
14. Select the Login with Token and paste your token in the Token textbox and click the Add Account button as shown in the image below.<p/><image src="./xstep13.png" height="300"></p>
15. Now, go back to **YOUR** repo and click the green <span style="background-color:green; color:white;">Code</span> button and then copy the URL by clicking on the copy button as indicated in the image below.<p/><image src="./xstep15.png" height="250"></p>
16. Open up IntelliJ and use the Get from VCS button to clone the repository.<p/><image src="./xstep16.png" height="300"></p>
17. Paste the assignment repository URL in the URL field and make sure to select the directory in which the assignment will sit.  IntelliJ will add the name of repo to the Directory path.  If it does not, please add the name of the assignment directory.  For example, if the directory is <span style="color:blue;">C:\Users\JohnSmith\Documents</span>, make sure to add the name of the assignment.  In my case, this should be changed to <span style="color:blue;">C:\Users\JohnSmith\Documents\recitation0</span>  <p></p><strong>Click the link to download and install Git, if asked.</strong><p><span style="color:red;"><strong>WARNING:</strong>  If you do not add a folder name, IntelliJ will put all the project files in the Documents folder</span>.</p>
18. Press the Clone button.  IntelliJ will create the folder for you and place the assignment code in the demo-github-classroom-rasamny folder under the Documents folder.
19. Your workspace should now look like the image shown below.<p/><image src="./xstep19.png"></p>
20. Now, to run and test the provided Java code, you will need to create a run configuration. Click on the run configuration button as shown in the image below.<p/><image src="./xstep20.png" height="400"></p>
21. Select Add New Configuration and then select Gradle from the menu as shown in the image below.<p/><image src="./xstep21.png" height="300"></p>
22. Give the configuration a name, for example <strong>Recitation0 Test</strong>, and type <strong>test</strong> in the run textbox then click OK to complete the run configuration.<p/><image src="./xstep22.png" height="300"></p>
23. Now press the green play button and notice that the test will fail.<p/><image src="./xstep23.png" height="350"></p>
24. Add "Hello World!" so that the following line of code reads ```System.out.println("Hello World");``` and then run the test again by clicking on the green play button.  You should now see that the test suucceeds!
25. You now need to commit the changes you made and push the changes to your repository on Github. Select the Commit tab as  shown in the image below. <p/><image src="./xstep25.png" height="350"></p>
26. Select all the files that have changed and type a message in th text box as shown in the image, the message should summarize the work done at that point, and click commit and push button.<p/><image src="./step31.png" height="400"></p>
27. Click on the push button in the next window to complete the submission.<p/><image src="./xstep27.png" height="300"></p>

### Congratulations!  You now have completed your first Java assignment!
