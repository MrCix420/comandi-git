*************** Comandi principali ***************
	- URL Video: https://www.youtube.com/watch?v=NVpwCzeFPD8&list=PL9MslR9MhrJbO7u34sgR3J6iMqkFmVenG
	- URL DOWNLOAD: https://git-scm.com/downloads
	- git --version
	- git init ( creazione cartella git )
		- echo hello > file01.txt
		- cat .\file01.txt
	- git status
	- git add .\file01.txt
	- git commit -m "First commit" -m "Descrizione"
	
	*** git add --> Working Directory --> Staging Area ( index )
		git commit --> History ( repository )
		
	- git restore --staged file02.txt
		Staging Area ( index ) --> Working Directory
	- git log
	- git log -oneline --reverse
	- git commit --amend
	- git reset
		--soft ( staging Area ) --> removed commit
		[--mixed] ( Working Directory ) --> removed commit
		--hard --> removed commit and delete file
		*** git reset --soft HEAD~1
		*** echo desktop.ini debuglog.log > .gitignore
	
	#### BRANCH etichetta/puntatore
	
	- git log --all --decorate --oneline --graph
	- git branch nome_branch
	- git checkout nome_branch
	- git commit -am "Added new line"
	- git diff nome_branch..nome_branch
	- git merge nome_branch
	- git branch --merged
	- git branch -d fix ( branch unito )
	- git branch -D fix ( branch non unito )
	- git checkout -b bugfix
	
	#### Server remote
	
	
