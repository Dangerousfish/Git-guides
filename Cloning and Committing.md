![image](https://user-images.githubusercontent.com/30146283/190242710-e1e5c5b2-0f18-4e9a-b9a5-ee10c2b49279.png)

***Requirements***

1. GitCLI needs to be installed:

  - **Windows** - https://gitforwindows.org/
  - **Linux** - sudo apt-get install git-all / dnf install git-all
  - **Mac** - https://sourceforge.net/projects/git-osx-installer/files/git-2.23.0-intel-universal-mavericks.dmg/download?use_mirror=autoselect

You will also need the GitHub extension for Visual Studio Code, via Terminal:
  ```
  ext install GitHub.vscode-pull-request-github
  ```

***Cloning a Repository in Visual Studio Code***

1. Locate a Git Repository that you wish to use and clone this to your local machine
  
  - To do this, copy the .git URL from the repository you wish to clone:
  
  ![image](https://user-images.githubusercontent.com/30146283/190231212-3be640b6-f5c1-45fc-9a95-a9ebb630cbf5.png)
  
  - Now open up a terminal window inside of Git and browse to the folder where you wish to store your files
     ```
     cd ../MyFolder
     ```
     
2. Clone the Git Repository
    ```
     git clone <gitURL>
    ```
    
3. Wait for the files to finish downloading and unpacking
  
  ![image](https://user-images.githubusercontent.com/30146283/190238567-40f1e3e9-b679-4aed-ae42-89df69927ebd.png)

4. In Visual Studio Code, open the folder you've just cloned to: 
   
  ![image](https://user-images.githubusercontent.com/30146283/190238761-a166b44b-0f96-46ba-9253-3b09a8de6316.png) 
  
  ![image](https://user-images.githubusercontent.com/30146283/190238802-9ef71566-1c80-4787-a65f-018285e1649e.png)

5. Make changes to the code and when you're ready to commit them to GitHub, move on to the next step.

***Committing changes from Visual Studio Code to GitHub***

1. To commit our changes, we now need to first login to GitHub. In your Terminal Window, enter the following command(replace with your GitHub email address):
  ```
  git config --global user.email "email@example.com"
  ```
  
2. Now that you're logged in, navigate to "Source Control", after making a change to the local version of your code.

3. You should see in the left nav-bar, all the changes that you have recently made.
  
  ![image](https://user-images.githubusercontent.com/30146283/190240785-7d63e8b9-8a7d-4f71-9571-0dbfb24f97e8.png)

4. Add a comment to your changes.
  
  ![image](https://user-images.githubusercontent.com/30146283/190240848-2fa0e800-e68b-464d-b719-47f12ee5e779.png)

5. Click Commit.

6. Staged changes allow changes to be published to different brances and undergo further scrutiny. You can stage these first, or press yes to commit directly to GitHub.
  
  ![image](https://user-images.githubusercontent.com/30146283/190241084-ab09eaf1-2a71-45a6-894e-52cd4c13dc5a.png)

7. Finally, press the "Sync Changes" button, to submit a new pull request.
  
  ![image](https://user-images.githubusercontent.com/30146283/190241830-09c401ca-175c-4807-a4f3-1c8833ea7a26.png)

8. That's it! Your change has been commited. Head on over to GitHub and check out your commital :)

  ![image](https://user-images.githubusercontent.com/30146283/190242018-eaeb7e8f-c258-45fb-b588-c410a79fe995.png)
