	### Comandi principali 
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
	- git remote ( lista nomi reg in precedenza )
	- git remote -v ( lista completa con URL )
		- cat .git/config ( file di configurazione )
	- git remote show nome_server
	- git remote rename nome_server nuovo_nome
	- git remote remove nome_server
	- git fetch ( retrive from server )
		- git fetch upstream ( retrive from server master )
	- git pull ( merge e fetch )
		- git pull upstream ( merge e fetch )
	- git clone URL nome_git_clone
	- git push ( deploy to server )
	- git remote add upstream url_origin_project 
	
