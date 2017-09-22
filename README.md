# intellijgittest
IntelliJ to GitHub Test

Just Create the Project. 
In Project Settings, Give Login Credentials for Github

On Main Menu, Click on VCS -> Import into Version Control -> Share Project on GitHub

Share Project on Github window, Enter Description. Respository name which is same as project is already pre-filled. 
If you want to change the name, you can do it here.
Click on Share

Window with title, Add files for initial commit is displayed. 
Select only the ones you want, do not select and iml or .idea directory. These are intellij config files

Commit message is prefilled.
Click on OK button.

Thats it!

Once you confirm that the files have been uploaded on your account in github. Add a README file. 
This file should contain information regarding how to execute your project, parameters used etc. 

Once completed, write a commit message and click on Ok button
Go back to IntelliJ Project and select VCS-> Update Project. This will "Pull" the changes (current README file into your project)
IF you do not perform this state, you will be unable to perform and more commits, because git is not synced up. 

