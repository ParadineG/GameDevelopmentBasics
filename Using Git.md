# Using Git

## Install Git related stuff to desktop (once per PC)

0. Install **git** (https://git-scm.com/download/win) with default options.
1. Install **git-lfs** (https://git-lfs.github.com/) with default options. 
2. Install **GitHub desktop** (https://desktop.github.com/) with default options.

## Clone your project to PC (once per PC)

0. Launch GitHub desktop.
1. Login to GitHub (File->Options->Accounts->Github.com Sing In).
2. Fill with your real name and email (File->Options->Git->Name & Email) and click Save.
3. Create a Clone from server project (File->Clone Repository)
4. Select GitHub.com and pick your Repository.
5. !!! Set Local path D:\GameDevelopmentBasics\YourName\ if on university PC (create folders if needed). Otherwise, set it where you expect it to be.
6. Then click on **clone** button.
7. Then click on **Current repository** again and from there mouse right-click on your selected repository and select **Open in Command Prompt**. (if it did not initialize lfs automatically)
8. In **Command Prompt** write **git lfs install** and click enter. (if it did not initialize lfs automatically)
9. Now you can open it via game project.


## Uploading changes (once per change)

0. **Do Fetch or Pull each time before you start modifying code or assets on game!**

1. Open GitHub Desktop and login.
2. Now commit by filling *Summary* with "Write here what you changed" and click *Commit to master*.
3. Now click Fetch/Pull origin to download all changes made by other.
4. If you changed same file same time (then here it will warn).
5. After that click Push to upload your changes.
6. Congratulations! You changes have been uploaded to GitHub.

## For paid packages

1. Add them to ignore list in .gitignore file or before committing them.
2. Share those packages via WeTransfer or similar.