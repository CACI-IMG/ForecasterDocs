# Releases

## Version 3.3 (March 2018)

This release sees the introduction of new interval level models, as well as the ability to add in manual forecast overlays. Links between projects have been added, so you can now read in forecasts from one project into another. Installation is now extremely simple, through a completely integrated R environment.

These changes are since version 3.1, v3.2 being an internal release.

#### Headlines

1. Interval level Smoothed Profile models are added, which give more weight to recent weeks, and also let you add in a proportion of the previous years’ profile. This can be helpful in modelling seasonal changes with minimal lag
2. Interval level Principal Components models are added. These work in a very different way, by determining a set of standard weekly profiles, then creating forecasts as a weighted combination of those profiles. This allows the use of different profiles at different times of year, or different intraday profiles in bank holiday periods
3. All interval profile models can now be used to match daily (or weekly) totals provided by another model
4. Forecasts can be read in from other projects. This can be especially helpful when a business driver is not known into the future. Forecasts can be created for this driver in a separate project, and can then be read into the main project to use as an input
5. Manual overlays can be applied to the main models, in order to overlay additional business knowledge on top of the data-driven forecasts
6. Simpler installation through a completely integrated R environment

#### Usability

1. Ability to freeze columns in the data grid –especially useful for interval level modelling, when you want to keep track of date and time as you scroll across the table
2. New data columns can now be added within the Forecaster: useful for creating manual data overlays
3. When setting up data exporters in a workflow, column selection is now much more flexible, and columns can be specified wither by index or by type (Target, Input, Forecast, etc)…

#### Other

1. External Processes have been added to workflows, so any custom exports or other processes can be automated

## Version 3.2 (July 2017)

This release sees the introduction of new interval level models, as well as the ability to add in manual forecast overlays. Links between projects have been added, so you can now read in forecasts from one project into another.

#### Headlines

1. Interval level Smoothed Profile models are added, which give more weight to recent weeks, and also let you add in a proportion of the previous years’ profile. This can be helpful in modelling seasonal changes with minimal lag.
2. Interval level Principal Components models are added. These work in a very different way, by determining a set of standard weekly profiles, then creating forecasts as a weighted combination of those profiles. This allows the use of different profiles at different times of year, or different intraday profiles in bank holiday periods.
3. All interval profile models can now be used to match daily (or weekly) totals provided by another model
4. Forecasts can be read in from other projects. This can be especially helpful when a business driver is not known into the future. Forecasts can be created for this driver in a separate project, and can then be read into the main project to use as an input.
5. Manual overlays can be applied to the main models, in order to overlay additional business knowledge on top of the data-driven forecasts.

#### Usability

1. Ability to freeze columns in the data grid –especially useful for interval level modelling, when you want to keep track of date and time as you scroll across the table
2. New data columns can now be added within the Forecaster: useful for creating manual data overlays
3. When setting up data exporters in a workflow, column selection is now much more flexible, and columns can be specified wither by index or by type (Target, Input, Forecast, etc)…

#### Other

1. External Processes have been added to workflows, so any custom exports or other processes can be automated

## Version 3.0 (February 2016)

This release has a large number of improvements across the board, with new workflow functionality as well as better and more integrated custom models. In addition, we’ve also made a wide range of other improvements and bug fixes, and public holidays are now available for a number of countries.

#### Headlines

1. New workflow functionality: This allows any set of projects to be automatically updated with a single button press, including re-importing data, re-forecasting, and exporting data if required. This lets large number of models to be updated very quickly. In addition, it lets non-power users update models easily, with no need for any specific knowledge of the models.
2. International public holidays: The Forecaster is shipped with public holidays for 7 countries, and this can be extended for new countries as required
3. New highly accurate Random Forests models: Random Forests have shown improved performance compared with regression. They are just as easy to use, and provide variable importance in the same way as for regression. Quite often, these models far outperform equivalent regression models, with no extra work for the user.
4. New derived column functions allow for more natural delay curves, and can now also skip weekends and public holidays as needed

#### Usability

1. Improved custom model integration: Custom models and script parameters are now accessed through bespoke dialogs, rather than as comma separated text. In addition, the Forecaster is now more directly integrated with the scripts, making for faster and more robust operation.
2. Look and feel improvements across the entire application and charts, including brand new logo and slicker importation for interval level data
3. Charts: Improved zooming, and new error bars
4. Search for column ‘goto’ functionality 

#### Bug Fixes

1. Various minor bug fixes

## Version 2.3 (January 2015)

This release has a raft of improvements across the board, but the main improvements are around data importation and project management. Due to a more flexible approach to data importation, columns can now easily be added or removed to projects, making it far easier to test and add or remove any business drivers. In addition, we’ve also made a wide range of other improvements and bug fixes.

#### Headlines

1. New improved CSV reader. File importation has been redesigned from the ground up for improved speed, flexibility, and robustness. Files can now be read in more quickly, and a wider variety of formats can be handled. All restrictions on additional columns or column ordering have been lifted. This means that new columns can be added in the raw data files at any point, with no need for rebuilding the project. This makes it easy to try new drivers, or remove any drivers that are no longer needed, while keeping the same project. In addition, trailing commas or thousand commas introduced by Excel now are handled smoothly (these last two points only apply to the direct csv importation, and not yet to custom script importation).
2. Column deletion is now allowed for all non-key columns. This means that any columns can be removed from projects if no longer needed.

#### Usability

1. Look and feel improvements across the entire application and charts, including brand new icons
2. Licence keys can now be renewed at any time via the About box
3. All application settings are now easily accessible via the Options dialog
4. Script Viewer now allows custom script viewing and editing from within the Forecaster
5. All settings are stored per user and do not require the registry, making the application easier to deploy, with less privileges needed
6. Model History is now saved automatically on Train

#### Bug Fixes

1. Various minor bug fixes, mainly around re-importation and custom models

