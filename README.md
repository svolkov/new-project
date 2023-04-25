Instruction

1.	Create ‘new-project’ folder:
		mkdir new-project
2.	Move inside the ‘new-project’: 
		cd new-project
3.	Initialize new repository: 
		git init
4.	Create file README.md: 
		touch README.md
5.	Insert one-line title into the README.md.
6.	Prepare README.md for committing:
		git add README.md
7.	Perform commit:
		git commit -m 'init'
8.	Create public repository ‘new-project’ on GitHub
9.	Assign remote repository to the local:
		git remote add origin https://github.com/svolkov/new-project.git
10.	Push the local repo on the public:
		git push -u origin main
11.	Create new branch ‘development’ and check it out:
		git checkout -b development
12.	Make changes in the README.md
13.	Prepare README.md for committing:
		git add README.md
14.	Perform commit:
		git commit -m 'Complete instruction'
15.	Move to the ‘main’ branch
		git checkout main 
16.	Merge ‘develop’ into ‘main’
		git merge develop
17.	Check status – local repo should be 1 commit ahead of the remote
		git status
18.	Push the local repo on the public:
		git push origin main

