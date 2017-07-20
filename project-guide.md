### Suggested Key Points of a Project:
Leverage recent trends and patterns in technology
- Be witty and whimsical in nature
- Be agnostic of opinion or stereotype
- Be clear and concise in communicating objectives and outcomes to both a student and instructor
- Be clearly written with good grammar
- Be visually appealing to the user
- Provide supporting resources and next steps

### Creating a New Project Repo in GitHub
1. Create a new repo in your GitHub profile or on your Organization's profile.
2. View your profile or organziation's profile and click on the repositories tab at the top. You will see a list of your repositories pop up. Click on the green button that says 'New'.
![Creating a New Repo](https://github.com/junior-devleague-educators/project-template/blob/master/assets/Screen%20Shot%202017-07-20%20at%2011.24.05%20AM.png)
2. Name your new project repo. Name should be all lowercase and words should be separated by dashes, not spaces. Initialize your repo with a README.md (which can be modified later).
![Initialize README.md](https://github.com/junior-devleague-educators/project-template/blob/master/assets/Screen%20Shot%202017-07-20%20at%2012.15.04%20PM.png)

### Project Description

Suggested format for description:<br> 
[*level of project*] *Language and/or framework* - *Brief list of objectives/concepts covered in the project* <br>
Ex:<br>
![Project Description](https://github.com/junior-devleague-educators/project-template/blob/master/assets/Screen%20Shot%202017-07-20%20at%2012.18.42%20PM.png)<br>
**Note:** *Project descriptions for more visual projects should include a link to GitHub page for showcase later on.*

### Clone From GitHub to Local Machine
1. Click on the 'Clone or Download' button and a drop down will appear. Make sure you select HTTPS and copy the url.<br>
![Clone Img in GH](https://github.com/junior-devleague-educators/project-template/blob/master/assets/Screen%20Shot%202017-07-20%20at%2012.25.53%20PM.png)<br>
2. In your terminal navigate to the directory you want to put your project in and follow these commands:
- `git clone` *paste the url you just copied here* ex: `git clone https://github.com/nat-nat33/my-new-project.git`<br>
![Git Clone](https://github.com/junior-devleague-educators/project-template/blob/master/assets/Screen%20Shot%202017-07-20%20at%201.04.19%20PM.png)<br>
-`ls` to list the contents of the current directory and check to see if you cloned correctly. The new project should show up.
- `cd` *name of the project directory you just cloned* ex: `cd my-new-project`<br>
![change directory](https://github.com/junior-devleague-educators/project-template/blob/master/assets/Screen%20Shot%202017-07-20%20at%201.04.33%20PM.png)<br>
- You should now be in the master branch of your new project.
3. Open your new project in sublime.
4. In your terminal add any directories/files necessary for the **students** to start the project to the **master** branch. **Note:** Remember you have to add files to the directories in order for you to push them up to GitHub. You can create temp files in order to bypass this.
5. Push your files up to your master branch. Files should just be initial files needed to start the project.
6. Check your GitHub to see if your files are synced up online.
7. In your terminal create a new solutions branch off the master branch by using the following commands:
- `git checkout -b` *name of your new solutions branch in quotes* ex:`git checkout -b "super-secret-branch"`<br>
![Git Checkout Img](https://github.com/junior-devleague-educators/project-template/blob/master/assets/Screen%20Shot%202017-07-20%20at%201.05.24%20PM.png)<br>
8. Double check to see if you are in the newly created branch.
9. Sublime should still be open and it will automatically switch you to that new branch, nothing on the screen in sublime will change.
10. Start to code a working solution in Sublime. When you are done, push your changes up to that branch using the following command:<br>
- `git push --set-upstram origin super-secret-branch`

### Tips and Suggestions
- Include as many images and screenshots to help students with the completion of the project or to make the project fun.
- Try to incorporate school spirit or modern trends into projects to keep students engaged.
- Include links to images or assign tutorials prior to assigning the project to solify concepts covered in the project.
- Use your team/organization's Slack channel to communicate changes to the classroom or provide any additional resources. 
- Encourage students to use Slack to ask questions and or send resources they've found.
- Use the **Hawaii Educators in Technology** Slack for ideas or assistance in creating projects.
- Feel free to draw inspiration from open source resources online like GitHub, w3schools, Stack Overflow, Medium.com, and Jr.Devleague's github https://github.com/junior-devleague. 
- Always add stretch goals for students who get ahead.
- If students finish projects early have them help other students who are still completing their projects. 
- If projects are more advanced, you may want to include a screenshot of the finished project to help guide students in their development process.
- Be clear in your instructions, if it's a bigger project, make sure students wire-frame or map out their ideas first and then stick to that plan to complete their MVP.
- For projects that are more visual, have students create a GitHub page to showcase their work.

### Reference Repos
- Feel free to create informative repos in GitHub for reference. 
- Include link to reference repos within the project.
- Reference repos should be informative, descriptive, and should include as many visuals possible to help students practices development processes and workflows.
