# Solution
While a project holds a single forecast, a solution represents a single workspace which may hold any number of individual projects.

## Solution Hierarchy

Once a new solution has been created or loaded, its structure can be seen in the Solution Explorer window (by default to the left of the screen).  A solution may contain one or more projects. The projects can be related to one another, such as projects with the same dataset but with differing forecasting models, or they can be completely unrelated but grouped in the solution for convenience. For example, all call volume forecasts in a particular contact centre could be grouped into one solution. The image below shows an example where projects for Motor, Home and Travel have been grouped in the same solution, together with a range of different forecasting techniques for Motor Sales.

![Solution Hierarchy](imgs/Solution_SolutionHierarchy.png)

In this example, you can see a number of sub-forecast projects within the Motor Sales forecast.  Grouping forecasts together like this makes it easier to manage solutions, which is particularly valuable when dealing with larger numbers of forecasts. It can often be really useful to keep forecasts from a number of models side by side, so you can compare the relative performance of different forecasting models.


## Managing Solutions

A number of management activities can be carried out on Forecaster Solutions - all under the *Home* tab.

![Home Tab Ribbon](/getting-started/imgs/Home_Ribbon.png)

### Creating a New Solution

The New Solution button (or quick keys `Ctrl+N`) is used to create a new forecast solution. A solution can contain any number of projects, each with their own data and forecasting models.

![New Solution](imgs/Solution_NewSolutionButton.png)

When creating a new solution, you're given the option to enter a solution name and also, if needed, change the location of the solution folder. 

![New Solution Name & Location](imgs/Solution_NewSolutionWizard.png)

 Once these parameters have been specified, pressing the OK button creates the new solution. This new solution starts out with a single empty project called *Project1*.
 
 <!--For finding out how to add new projects to a solution, use the link below:

{% page-ref page="Projects.md" %}
-->

### Opening, Closing and Saving a Solution

A solution in Forecaster can be managed through the options available in the Home Tab.

![Solution Management](imgs/Solution_Management.png)


*	To open a solution, click on the **Open** button, select the relevant solution file and select OK.  Alternatively press the `Ctrl+O` keys to access the same open solution dialog
*	To close a solution, click on the **Close** button.  If the solution has had some changes before the last save, then the application will ask you if you'd like to save these changes
*   To save a *project*, click on the **Save** button
*	To save a *solution*, click on the **Save Solution** button.  This will then display two save options:
    -	**Save**:  Saves the solution under the current name.  Files can be saved directly by pressing the `Ctrl+S` keys
    -	**Save As**: This lets you save the solution under a new name or in a different location


All these actions can also be found on the quick access toolbar, right at the top left of the Forecaster window.

![Quick Access Toolbar](/getting-started/imgs/Solution_QuickAccessToolbar.png)


## Recent solutions
Links to recent solutions can be found either using the **Recent Solutions** button, or in the main window when you have the *Home* tab selected.  

## Moving solutions
When a solution is saved, a solution directory is created and a number of files are placed in this directory.  If you'd like to move a forecast solution without using Save As (for example if you have multiple solutions to move, or if you want to move rather than copy the solution), you can simply copy the whole solution folder to the new location.

## Deleting solutions
You can't delete a solution from within Forecaster, so the best way is to delete the solution folder using Windows Explorer (as you would for deleting a Word or Excel document - apart from the fact you're deleting a folder not a single file).





