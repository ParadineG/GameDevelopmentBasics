# Forking game project for homework and missed classes

## Forking on GitHub (once per project)

0. Log in on to GitHub.com
1. Go to url given by teacher, (to his project page) and click fork button on top-right.
2. Sing In to GitHub and go to https://github.com/ and click on *Start a project*.
3. After forking go back to teachers project page (you will need it later).

## Install Git related stuff to desktop (once per PC)

0. Install **git** (https://git-scm.com/download/win) with default options.
1. Install **git-lfs** (https://git-lfs.github.com/) with default options. 
2. Install **GitHub desktop** (https://desktop.github.com/) with default options.

## Setting up and cloning project to PC (once per PC)

0. Launch GitHub desktop.
1. Login to GitHub (File->Options->Accounts->Github.com Sing In).
2. Fill with your real name and email (File->Options->Git->Name & Email) and click Save.
3. Create a Clone from server project (File->Clone Repository)
4. Select GitHub.com and pick your Repository.
5. !!! Set Local path D:\GameDevelopmentBasics\YourName\ if on university PC (create folders if needed). Otherwise, set it where you expect it to be.
6. Then click on **clone** button.
7. Then click on **Current repository** again and from there mouse right-click on your selected repository and select **Open in Command Prompt**.
8. In **Command Prompt** write **git lfs install** and click enter (if does not initialize before).
9. On *GitHub website* open original project git page you copied and copy link by clicking on **Clone or download** and copy link from there.
10. In **Command Prompt** write **git remote add old-origin** *paste URL from teachers repo to this commands end* (via right-mouse click in cmd) and click enter. Ex: *git remote add old-origin http://git.org/sth.git*
11. In **Command Prompt** write **git lfs fetch --all old-origin** and click enter.
12. In **Command Prompt** write **git lfs push --all origin** and click enter.
13. In **Command Prompt** write **git lfs pull** and click enter.
14. And now you can open it via Unity or UE4.
