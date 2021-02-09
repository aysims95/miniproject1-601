# *What is GitFlow* :memo:
GitFlow is a branching model for Git that is very well suited for collaboration and scalling the development team. Benefits of GitFlow include parallel development, collaboration, release staging area and support for emergency fixes.

# *How GitFlow Works* :bulb:
*	 New development are built in **feature branches**.

![](/Images/GitFlowFeatureBranches.png)

* 	Feature Branches are branched off of the **developed branch**. Finished features/fixes get merged back into **developed branch** when they are ready for release.

![](/Images/GitFlowDevelopBranch.png)

*	 A **release branch** is created off of **develop** once it's time for release.

![](/Images/GitFlowReleaseBranch.png)

* 	The code **deploy->test->fix->redeploy->retest** is deployed in the **release branch** until the results are suitable to the users' likings. Any changes or fixes are done directly in the release branch. Once the release is complete, the **release branch** is merged into both  **master** and **develop** to ensure all changes made in release branch make it into the new development.

![](/Images/GitFlowMasterBranch.png)

* 	The **master branch** only tracks released code, so the only commit in master are from **release branch** and **hotfix branches**. **Hotfix branches** are used for emergency fixes and get merged back into both **master** and **develop** to store all the changes. 

![](/Images/GitFlowHotfixBranch.png)




