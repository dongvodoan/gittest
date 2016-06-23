#Stydy about git + github in ubuntu
*Install git in ubuntu
  sudo apt-get update
  sudo apt-get install git
  -- you can see version of git that you installed by line command
  sudo git --version

*Config git to connect to github when you commit ... above serve
  @way 1:
	git config --global user.name "username your account github"
	git config --global user.email "email that you register account in github"
  ->OK! when you push up master that it will request username and password account of github
  @way 2: SSH key

  @way 3: SSH file

*Command
	@create forder
		- mkdir <name repo>
		- cd <name repo>
		- git init
	@create new repository in github
	@create file in new forder
		- echo "# name folder" >> <name file>
	@commit
		- git add <file> or git add . //all file
		- git commit -a/ -m "information changes"
	@pull
		- git pull URL //https://github.com/at-dongvd/gittest.git
	@push
		- git push URL //https://github.com/at-dongvd/gittest.git
	@review changes
		- git log
