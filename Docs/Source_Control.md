# Source_Control

Modern applications require teams working together.  Traditionally we want to have our applications, projects, or code on a local space in which to work, test, and validate.  As the teams grow it might become less and less reliable to continally email projects back and forth.  This can often create 'project bloat' on local servers.  It is not uncommon to have multiple projects saved to make sure data is not corrupted or lost.  All of this falls in the realm of - 'now where did i put the right one.....'.  Hence:

## What is Source Control (version, code,etc)

In order to clean up this source bloat and assist teams with version management there are now many systems out that are free, or paid for, that teams can use to protect and share data in a centralized environment.  Teams connect to these environments, download copies and upload changes.  These changes are tracked, often controlled by role based access control (RBAC), and securely stored among many other features.  For this document we will be using Github, a commonly used online source control space.

## Git_Operations

To get started in source control we will use six main operations in Github.  
- [Clone](#Clone)
- [Pull](#Pull)
- [Branch](#Branch)
- [Add](#Add)
- [Commit](#Commit)
- [Push](#Push)

### Clone

In order to begin working with the projects, or repositories, it needs to be cloned locally.  No project should be edited from the 'master files' located within the central repository.  While they can be edited here this removes the ability to audit and control who is working on the code.

### Pull

Pull allows a user to update the local repository with any changes that have occured since the project was last worked on.  General best practices would require users to make sure their local repository is up to date before working on new material from that repository.  This keeps code changes linear and helps to not cause issues when multiple people are working on the same project often.

### Branch

Branches allow versions of the initial code without affecting the master information.  With branches you can edit code, verify and test.  Once satisfied with the changes the code can then 

### Add

In order to let Github know that a piece of code needs to be updated the software requires a flag, 'Add', to be set on the working data.  This helps keep projects clean of changes that were not meant and forces the user to promote code from 'working' to 'ready'.

### Commit

Once code is ready for uploading to the central project it will need to be commited, or acknoledged, as ready for changes to be moved to the central repository.  Committing code also requires the user to comment on the changes that are being updated.  This is a working record of the changes via comments to let other users in the project know what has been changed since the last update.  Ususally these comments are in the present tense as a best practice as code repositories are 'living' environments.

### Push

After committing changes in the local repository they need to be pushed to the central repository.  This is the only step that will actually change the living data in the repository.  Once pushed the central repository will now reflect all changes that have occured.  

## Installing GIT
GIT is a service that runs on your local machine and can interface with a GIT repo in a private or public location. One of the most common is GitHub which we are going to use in this example but there are others such as GitLab. Atlassian and others. 

Installing GIT is relitively simple. Take a look at the main page [here](https://git-scm.com/)
There are installers for all major operating systems, or if you are more comfortable you can use CLI installers such as yum, get-apt, brew and more. 

### Configuring GIT with GitHub

Once you have GIT installed in this example we are going to create a repo and connect it to GitHub. Its worth noting that GIT always works with a directory stucture on your local machine. GitHub is mearly the duplication, aggregation of that directory as your working with others to facilitate that multi-user collaboration. As mentioned earlier in this section you start by cloning (if you are addiing to) or forking (if you want a seperate version) a repo to get started.

Git in controlled by X files. These control things like Y. If you want to change them you can do so by directly editing those files or doing the same actions through an IDE.

Connecting a GIT repo to GIT hub can be done via CLI or through and IDE. We will discuss both options.

First lets fork the repo.

#### Connecting to GitHub

