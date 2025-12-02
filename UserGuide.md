# Project management - User guide

# Accounts 

## Creating an account

To create an account, click on the **Sign Up** button in the upper right corner of the site. You will be met with a form where you will be able to input your future username, e-mail address and your password.
Click **Sign Up** to create an account.
If you already have an account, you can directly click on **Log In** instead.
**Warning**, as Project Management doesn't have an account retrieval system, make sure to not lose your password.

## Log in into your account

To log in your account, click on the **Log in** button in the upper right corner of the site.
Fill in your e-mail and password, then click on **Log in**.
If both entries are correct, you will then be able to access the rest of the site.

## Log out

If you want to exit your account, just click on the **Log out** button in the upper right corner of the site.
You will be logged out of your account, and anyone using your computer will not be able to access your account.

# Projects

## List of projects 
The main page of Project Management, contain the list of all of your projects.

## Creating a project

To create a project, click on the **Create Project** button to the right of **My Projects**. Fill in the name of your new project, then click the new button **Create Project** under the form. You will then be taken to the page of your project.

# Project Management

## Go back to the list of projects

Once you are on the page of your project, just click on **the button with your username** to go back to the main page.

## Projects Settings

To modify your project, go to **Settings**. You will then be able to:

### Rename the project & Change the description

The first section of the Settings page is a form that allow you to change the name of your project and add a description.

### Add members

The second section of Settings allow you to add new members to the project with a specific role.

Enter either the e-mail address or the username, select the role you want to attribute, then click **Invite**.

- Scrum master can do everything in backlog, sprint and release. They can also change the role of users, except for the owner. The rest of the settings are inaccessible.
- Developer can create and edit Task.
- Viewer can only view the content of the project.

(The project creator can do everything).

### Edit members

You can remove a member or change their role. Just click on the **Remove** button to the right of a user to remove them. And to select the role you want to attribute, click on the button **with their current role on it**.

## Delete project

Click on the **Delete Project** button to erase your project.
**Warning**, this is a permanent deletion.

# Backlog

Where you can handle your Users Stories and their respective task.

## User Story

### Creating a User Story

To create a project, click on the **Create User Story** button to the right of **Backlog**. Fill in the **name**, **description**(optional), select the **Priority** and **Story Point** of your new US, then click the new button **Create** under the form.

### Editing a User Story

To edit a US, simply click on it on the backlog page. It will take you to the same form as the one you used to create it. You can either **Cancel** the operation, **Update** for the field you changed, or **Delete** the US by clicking on the corresponding button.

## Tasks

A task is a component of a US. You will need to create a US first, to add a task to it. **Warning** Since tasks are a component of a US, deleting said US will delete all of it's task as well.

### Creating a Task

To create a task, click on the **Create Task** button inside a US. Fill in the **title** and **description**(optional), then click the button **Create Task** under the form.

### See the tasks inside a US

To see all the tasks inside a US, click the **little arrow on the left of your USID** (written like 'US1'), click on it again to hide them.

### Editing a Task

To edit a Task, simply click on it in the corresponding US. It will give you the same form as the one you used to create it, with two new fields: 
- Status: the current status of the task, either: "To Do", "In Progress" or "Done"
- Assigned To: the current project member that have to do the task (can be "Unassigned".
. You can either: **Cancel** the operation, **Update** for the field you changed, or **Delete** the US by clicking on the corresponding button.

# Sprints

A sprint is a period of time when work can be focused on specific US.
Click on the **Sprints** button on the left side to access the sprint page.

### Creating a Sprint

To create a project, click on the **Create Sprint** button to the right of **Sprints:**. Fill in the **name**, **description**, select the **Start Date** and **End Date** (must be after start date) of your new sprint, then click the new button **Create** under the form.

### Editing a Sprint

To edit a sprint, simply click on it on the sprints page. It will take you to the same form as the one you used to create it. You can either: **Cancel** the operation, **Update** for the field you changed, or **Delete** the US by clicking on the corresponding button.
**Sprints cannot be edited after Completion**
**This only concern the main characteristic of a sprint, see rest below**

### Assigning US

A sprint contain a list of the US you aim to achieve between the start and end Date of the sprint. You can assign US to the sprint by clicking the **Assign US** button, in the bottom right corner of the current Sprint section. A popup with all US will appear, select the one you want and click on **Assign Selected** to assign all selected US to the current sprint.

To see all the tasks assigned to the sprint, click the **little arrow on the left of your SprintID** (written like 'Sprint 1'), click on it again to hide them. 

### Start a sprint

To start a sprint, click on the **Start** button on the upper right of the current sprint section. 

### End a sprint

To end a sprint, click on the **End** button on the upper right of the current sprint section. 
**Ending a sprint will prevent all further update**
You will be prompted to choose what type of release, this sprint is for. Between "Patch", "Minor", "Major"
**See below for Release**

# Release

A release is an update version of your project.
Each release has an ID/name divided in 3 numbers in the form of a.b.c
- a: Major advancement of your project
- b: Minor advancement of your project
- c: Patch, AKA very small change to your project

## See the release

Click on the **Release** button on the left panel of the site.
For each release, you can see the ID/name, the release Date, and a small description.

## Edit the release

By clicking on the release you want to edit, you will be met with a new prompt.
The two field contain the description of the sprint ("Release for sprint <Name of the sprint\>" by default) and  it's release date.
You can change them both if it's more logical for you.
(Change the release to the day when a product is release instead of the day when its production was finished, for example).
You can either: **Cancel** the operation or **Update** for the field you changed.
