# Projects


The following section explains how to manage your projects in the Solution Explorer.  Once a solution has been created, there are number of management activities which can be carried out on projects within the solution.  Details are as follows:


## New Project
To create a new project, click on the **New Project** button from the *Home* tab.  You can then load data and build a model in the usual manner.

Alternatively, right-click on the solution name and select **New Project** from the solution options as shown in the image below. 
 
![New Project](imgs/Project_NewProject.png)



## Project Properties - Project Name
To change the name of any project within a solution, right-click the item of interest from the Solution Explorer view and then select the **Properties** option.  The following dialog lets you change its name, as shown in the image below.  You can also add some comments to the project should this be required.  Additional information on the creation date and time and creator of the forecast or project is also shown here.


![Project Properties](imgs/Project_ProjectProperties.png)


## Duplicate Project
To create a copy of a project, right click on the relevant project in the Solution Explorer and then click on **Duplicate Project**.  


![Duplicate Project](imgs/Project_DuplicateProject.png)

This creates a copy of the project, including data, model and settings. To show the connection between the two projects, in the Solution Explorer the copy is placed below the original project.
 


{% hint style="info" %}
A project duplicate can be repeated for as many levels as the user wishes, thus creating a comprehensive range of forecast projects and results.  Once all experimentation is complete, the best forecast can be selected.
{% endhint %}


## Add Existing Project
Forecaster lets you take a project from one solution and insert it into another.  This might be useful when consolidating forecasts from a number of different sources to create the ‘operational’ versions after a period of investigation.

To add an existing project to the current solution, right-click on the solution name in the Solution Explorer and select **Add Existing** from the list of options.  This will then open up a navigation window to allow you to locate the forecast of interest.  If you attempt to import a project with a name that already exists in the current solution, the system will ask you whether you wish to overwrite the existing project.  If you select no then the import process will be cancelled.



## Delete Project
A project can be deleted via the Solution Explorer by right-clicking on the relevant project and choosing **Delete Project**. Confirmation will be sought that you really do want to delete all components of the data.  Be aware that the project that will be deleted is the one that is currently active. 

![Delete Project](imgs/Project_DeleteProject.png)


