Locally:
1. mkdir directory_name					- make a new directory
2. cd directory_name					- make new directory the working directory
3. git init						- initializes directory (turns it into a repository)
4. echo "some text here" >> filename.txt 		- create a file (filename.txt) with some text
5. git add filename.txt					- adds file to staging area
6. git status						- optional: will show changes to be committed
7. git commit -m "message here"				- commits the new file
 
 
In Terminal 
1. pwd							- print the working directory 
2. cd directory_name					- optional: navigate to directory w/ Git repository 
							  if not already there 
Remotely (on GitHub) 
3. "New repository" button 
4. Repository name: directory_name 
5. Choose public or private 
6. Be sure HTTPS is selected 
 
In Terminal (use the command line to push a repository) 
7. git remote add origin https://github.com/YOUR_USERNAME/git_practice.git 		- first time only 
8. git push -u origin master 								- each time 
	 --> repeat steps 5 - 7 from "Locally" and step 8