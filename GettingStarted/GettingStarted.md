

## Solution 

### Solution Hierarchy

At this point it is sensible to talk about the hierarchy of a **solution**.  Once a new solution has been defined or loaded, its structure can be seen in the **Solution Explorer** window.  A solution may contain one or more **projects**.  The projects can be related to one another, such as projects with the same dataset but with differing forecasting models, or they can be completely unrelated but grouped in the solution for convenience.  For example, all call volume forecasts in a contact centre could be grouped into one solution.  Figure 5 demonstrates that forecast projects for Motor, Home, Pet and Travel can be grouped in the same solution.


**[ IMAGE Solution Explorer Example ]**


Each of these projects contains different sources of data, however, for the sake of simplicity it makes sense to group all of these forecasts in the same place.  For example, if other planners need to build forecasts in someone’s absence, all active forecast models will be in the same collection.

Notice in Figure 5 that within the Motor Sales forecast there are a number of sub-forecasts or **project snapshots**.  These snapshots represent a collection of Motor Sales forecasts that share common data with the project one level up.  The purpose of this hierarchy is to allow the user to keep a copy of all experiments considered valuable, for example a collection of forecast models that yield good predictions.


### Projects

To create a new project that does not inherit any data or models from other projects, select the New Project icon from the Home – Solution tab.  The user is then expected to load data and build a model in the usual manner.
Alternatively, right-click on the solution name and select New Project from the solution options as shown in Figure 37. 

**[ IMAGE ]**

### Project Snapshot
A project snapshot is a way of making an exact copy of an existing project.  To show the connection between the two projects, the copy is placed under the original project from which the snapshot was generated.  Please note that if there are any subsequent changes to the originating project, the changes will not be inherited by the previously defined snapshots.
To create a project snapshot, select the relevant project and then select the Project Snapshot icon from the Home – Solution ribbon, alternatively right-click the project of interest in the Solution Explorer and select the Project Snapshot option.  
 
 **[ IMAGE ]**

### Project Options
A copy of the project, including data, model and settings, will be created under the current project.  
A project snapshot can be repeated for as many levels as the user wishes, thus creating a comprehensive range of forecast projects and results.  Once all experimentation is complete, the best forecast can be selected.

###  Delete Project
To delete a project (or project snapshot) from within an existing solution, press the Delete Project icon located in the Home – Solution ribbon.  Confirmation will be sought that you really do want to delete all components of the data.  Be aware that the project that will be deleted is the one that is currently active.
Alternatively, a project or snapshot can be deleted via the Solution Explorer by right-clicking on the relevant project and choosing Delete Project.  The full list of options is shown in Figure 38. 

###  Add Existing Project
The CACI Forecaster permits the user to take a project from one solution and insert it into another.  This might be useful when consolidating forecasts from a number of different sources to create the ‘operational’ versions after a period of investigation.
To add an existing project to the current solution, select either the icon from the Home – Solution ribbon or right-click on the solution name in the Solution Explorer and select Add Existing from the list of options.  This will then open up a navigation window to allow you to locate the forecast of interest.  If you attempt to import a project with a name that already exists in the current solution, the system will ask you whether you wish to overwrite the existing project.  If you select no then the import process will be cancelled.

###  Properties
To change the name of any project or snapshot within a solution, right-click the item of interest from the Solution Explorer view and then select the Properties option, as shown in Figure 38.  The system will then display a simple dialog to allow you to change its name (Figure 39).  It will also give you the opportunity to add some comments to the project should this be required.  Additionally information on the creation date and time and creator of the forecast or project will be displayed.

**[ IMAGE ]**
