Create a new folder on your local machine ("PLPBasicGitAssignment").
Open a terminal or command prompt and navigate to the created folder.Follow the path
$ cd Desktop
$ cd PLPBasicGitAssignment
Initialize a new Git repository in your local folder.
$ git init
Link your local repository to the GitHub repository
$ git remote add origin https://github.com/eststacee/PLPBasicGitAssignment.git
Making changes and create a File. Add a simple text message ("Hello, Git!")
$ touch hello.txt
Committing Changes
$ git add hello.txt
$ git commit -m "Add hello.txt with a greeting"
Push the committed changes to your GitHub repository
$ git push -u origin master
