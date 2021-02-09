## Install Git For Mac

* Check to see if Git is Installed

![Git Logo](git-version.png)
 
* If so then you can skip this step if not then follow along:

	1.) Open Terminal and enter git --version it will install when prompt 
	
	2.)Configure your Git username and email using the following commands:
	
	git config --global user.name "Your name" $ git config --global user.email "Your email"


## Install Git for Windows



1.)	Download Git for Windows:
[Git](https://git-scm.com/downloads) - link!

![Git Logo](Download.png)


2.)	Browse to the download location,Double-click the file to extract and launch the installer.


![Git Logo](Browse.png)


3.)	Allow the app to make changes to your device by clicking Yes on the User Account Control dialog that opens.


![Git Logo](Allow.png)


4.)	Review the GNU General Public License, and when you’re ready to install, click Next


![Git Logo](Review.png)


5.)	The installer will ask you for an installation location. Leave the default, unless you have reason to change it, and click Next.


![Git Logo](Installer.png)


6.)	A component selection screen will appear. Leave the defaults unless you have a specific need to change them and click Next.


![Git Logo](component.png)


7.)	The installer will offer to create a start menu folder. Simply click Next.


![Git Logo](Next.png)


8.)	Select a text editor you’d like to use with Git. Use the drop-down menu to select Notepad++ (or whichever text editor you prefer) and click Next.


![Git Logo](texteditior.png)


9.)	This installation step allows you to change the PATH environment. The PATH is the default set of directories included when you run a command from the command line. Leave this on the middle (recommended) selection and click Next.


![Git Logo](path.png)


10.)	Most users should use the default. If you’re working in an Active Directory environment, you may need to switch to Windows Store certificates. Click Next.


![Git Logo](https.png)


11.)	It is recommended that you leave the default selection. This relates to the way data is formatted and changing this option may cause problems. Click Next.


![Git Logo](checkout.png)


12.)	Choose the terminal emulator you want to use. The default MinTTY is recommended, for its features. Click Next.


![Git Logo](emulator.png)


13.) Just click next because those are optional choices

14.) Click Finish, and your done

![Git Logo](finish.png)




                         * TWO COMMON COLLABORATIVE WORK FLOWS
                         * SHARED REPOSITORY MODEL
```
              * For small projects where you are basically in the same physical space
              * You are cloning the main repository.
              * Everyone has push and pull access to the central repo, so be careful and:
              * Never commit to the master directly.
              *Always do your work on a different branch from master.
              
              -BASIC SHARED REPOSITORY WORKFLOW

              * update your local repo with git pull origin master,
              * create a working branch with git checkout -b MyNewBranch
              * make your changes on your branch and stage them with git add,
              * commit your changes locally with git commit -m "description of your commit", and
              * upload the changes (including your new branch) to GitHub with git push origin MyNewBranch
              * Go to the main repo on GitHub where you should now see your new branch
              * click on your branch name
              * click on “Pull Request” button (URC)
              * click on “Send Pull Request”

```

FORK AND PULL MODEL

- This is the model used by U of T Coders on its own website and repos.
- The “owner”/”Project Leader” of the upstream repo assigns rights to “Collaborators”
- Collaborators do not have push access to main (upstream) repo
- Project Lead accepts Pull Requests (PRs) fro collaborators, reviews them, then merges them into main repo.

[Atlassian](https://www.atlassian.com/git/tutorials/install-git)
