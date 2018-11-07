# Setting up GitHub and creating group game project

## Create Empty Project on GitHub (once per project)

0. (if no account) Create account with default options.
1. (if no account) Confirm registration by e-mail!
2. Sing In to GitHub and go to https://github.com/ and click on *Start a project*.
3. Give Repository name and choose public.
4. Also Initialize with **README** file (this is where I expect to find info about game later).
5. Additionally add **.gitignore** file with Unity or Unreal template.
6. And finally click *Create Repository*.

## Install Git related stuff to desktop (once per PC)

0. Install **git** (https://git-scm.com/download/win) with default options.
1. Install **git-lfs** (https://git-lfs.github.com/) with default options. 
2. Install **GitHub desktop** (https://desktop.github.com/) with default options.

## Setting up and clone empty project to PC (once per PC)

0. Launch GitHub desktop.
1. Login to GitHub (File->Options->Accounts->Github.com Sing In).
2. Fill with your real name and email (File->Options->Git->Name & Email) and click Save.
3. Create a Clone from server project (File->Clone Repository)
4. Select GitHub.com and pick your Repository.
5. !!! Set Local path D:\GameDevelopmentBasics\YourName\ if on university PC (create folders if needed). Otherwise, set it where you expect it to be.
6. Then click on **clone** button.
7. Then click on **Current repository** and from there mouse right-click on your selected repository and select **Show in Explorer**  (*once per project*).
8. Add there file named **.gitattributes** (with dot!) from google classroom (one is for Unity and other for UE4, pick one) (*once per project*).
9. Then click on **Current repository** again and from there mouse right-click on your selected repository and select **Open in Command Prompt**.
10. In **Command Prompt** write **git lfs install** and click enter.
11. Also write **git add .gitattributes** and click enter, after that close **Command Prompt** even if there is LF related warning (*once per project*).
12. Rename temporally project folder by adding  sth to end maybe _temp or similar.


## Create Empty Game Project with game engine (once per project)

### Unreal Engine

0. Download Unreal Engine 4.20.x with Epic Games Launcher from [here](https://www.unrealengine.com/en-US/what-is-unreal-engine-4) and install it. Account creation is also required. Additional information (https://docs.unrealengine.com/en-US/GettingStarted/Installation) (default options are fine) (*once per PC*).
1. Launch *Epic Games Launcher* and from there select *Unreal Engine* -> *Library*-> Launch (4.20.x) 
2. Now go to *New Project* and select project of your choice, preferably under blueprint.
3. For settings pick ***Desktop / Console*** over *Mobile/Tablet*, ***Scalable 3D or 2D*** over *Maximum Quality* and ***No Starter Content*** over *With Starter Content*. (You can modify them inside project later).
4. Save them in D:\GameDevelopmentBasics\YourName\ if on university PC (create folders if needed). Your choice at your own PC. Also name the project same like GitHub and then click *Create Project*.
5. After that save all under  and close opened project.

### Unity

0. Download Unity Hub from [here](https://public-cdn.cloud.unity3d.com/hub/prod/UnityHubSetup.exe?_ga=2.135139825.1332452146.1541181023-708816826.1536157262) and install it. Account creation is also required. Additional information (https://docs.unity3d.com/2018.2/Documentation/Manual/GettingStartedInstallingHub.html) (*once per PC*).

1. Launch *Unity Hub* and from there select *Installs* -> *Official Releases*-> **Unity 2018.2.x** and click Download and install Unity (default options are fine) (*once per PC*).
2. When finished click on *New* to create new project.
3. Set project name same as original GitHub project name pick **Unity 2018.2.x** as Unity version.
4. Save them in same place as GitHub before renaming aka save them in D:\GameDevelopmentBasics\YourName\ if on university PC (create folders if needed). Your choice at your own PC. 
5. Pick 3D as template and turn off Unity Analytics.
6. After that save scene and save project under file menu and close opened project.

## Making first push to server (once per project)

1. Open renamed GitHub project folder and copy everything from it to Game project folder.
2. Then delete GitHub project folder.
3. Open GitHub Desktop, if it can not find the project then click on *Locate...* and set it to game project folder.
4. Now commit by filling *Summary* with "Setting up Unity/Unreal project" and click *Commit to master*.
5. Now click on Publish repository or Push.
6. Congratulations! You finished setting up project.

## For paid packages

1. Add them to ignore list in .gitignore file. or before committing them
2. Share those packages via WeTransfer or similar.