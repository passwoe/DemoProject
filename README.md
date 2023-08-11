# DemoProject

echo "# DemoProject" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/passwoe/DemoProject.git
git push -u origin main

How to work with Git & Github using Eclipse | Commit | Push | Branching | Pull Request | Merging

1)first creatge folder in your local for the use below command
		mkdir <foldername>
2)after go to the folder inside
		cd <foldername>
3)set the username using below command
		git config --global user.name "Your Name"
4)set the email using below command
		git config --global user.email "you@example.com"
5)check the username is set are not 
		git config --global user.name
6)check the email is set are not 
		git config --global user.email
7)to know the current user
		whoami
8)to know present working directory
		pwd
9) to know all files
		ls:it prints all current directory
		
10) to check git up and running
		git help
11) to create file 
		touch <file name.txt>
12)add local repository to github remote reposotiry
		git remote set-url origin https://github.com/passwoe/DemoProject.git
13 push the changes and folder 
			git branch -M main( master)
			(OR)
14) add branch to main
		git branch -M main
