# Github how-to-use documentation for Beginners
## Setting up a Windows Environment
* Goto https://git-scm.com/ and install git for windows
* Use special command line interface "Git Bash" which is easy to work with Git
* First we need to configure git on our local machine
  * git config --global user.name "TMK Computers"
  * git config --global user.email "computers.tmk@gmail.com"
  * git config core.editor "notepad++ -multiInst -nosession"
  * git config --edit --global
  
 # Creating git rerpositry in local machine
 * To create a new repository on local machine run below commands
   * git init DemoApp
   * cd DemoApp
   * ls -la
 * To check status of repositry 
   * git status
 * To create a new file REDEAME.md run below command
   * alias notepad="/c/Program\ Files\ \(x86\)/Notepad++/notepad++.exe" 
   * notepad README.md   
             OR
   * touch README.md   
 * Add Some content in README.md.I have added # Hello Seeya and Save this file.
 * Then check status again which shows status that we have an untracked file
   * git status
 * Track the changes in README.md file with command
   * git add README.md
 * If we have multiple new and edited files then we can track them all with a single command
   * git add .
* Then check status again which shows status that we have a staged file
   * git status
* Now we can commit the file with readable message
  * git commit -m "Intitial Commit"
  
* Creating git repository on GitHub.com
  * We can create a new repository on github.com with clicking on new New Repository button
  * Choose a unique name within your account for new repository and add description also
  * you have 3 options for working with newly created repository
  
* Create a new repository on the command line
  * echo "# sample-repo" >> README.md
  * git init
  * git add README.md
  * git commit -m "first commit"
  * git remote add origin https://github.com/tmk-computers/sample-repo.git
  * git push -u origin master

  
 

  
