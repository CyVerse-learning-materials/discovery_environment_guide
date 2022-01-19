> \<a href=\"<https://atmo.cyverse.org>\"
> target=\"blank\"\>Atmosphere\</a>

> \<a
> href=\"<https://wiki.cyverse.org/wiki/display/atmman/Atmosphere+Manual+Table+of+Contents>\"
> target=\"blank\"\>Atmosphere Manual\</a>

> \<a
> href=\"<https://learning.cyverse.org/projects/atmosphere-guide/en/latest/>\"
> target=\"blank\"\>Atmosphere Guide\</a>

> \<a href=\"<https://bisque.cyverse.org/client_service/>\"
> target=\"blank\"\>BisQue\</a>

> \<a href=\"<https://wiki.cyverse.org/wiki/display/BIS>\"
> target=\"blank\"\>BisQue Manual\</a>

> \<a href=\"<https://user.cyverse.org/>\" target=\"\_blank\"\>CyVerse
> User Portal\</a>

> \<a href=\"<http://learning.cyverse.org>\" target=\"blank\"\>CyVerse
> Learning Center\</a>

> \<a href=\"<https://wiki.cyverse.org>\" target=\"blank\"\>CyVerse
> Wiki\</a>

> \<a href=\"<http://www.cyverse.org/data-store>\"
> target=\"\_blank\"\>Data Store\</a>

> \<a
> href=\"<https://wiki.cyverse.org/wiki/display/DS/Data+Store+Table+of+Contents>\"
> target=\"blank\"\>Data Store Manual\</a>

> \<a
> href=\"<https://learning.cyverse.org/projects/data_store_guide/en/latest/>\"
> target=\"blank\"\>Data Store Guide\</a>

> \<a href=\"<https://de.cyverse.org/de/>\" target=\"blank\"\>Discovery
> Environment\</a>

> \<a
> href=\"<https://wiki.cyverse.org/wiki/display/DEmanual/Table+of+Contents>\"
> target=\"blank\"\>DE Manual\</a>

> \<a
> href=\"<http://learning.cyverse.org/projects/cyverse-discovery-environment-guide/>\"
> target=\"blank\"\>Discovery Environment Guide\</a>

> \<a href=\"<https://dnasubway.cyverse.org/>\" target=\"blank\"\>DNA
> Subway\</a>

> \<a
> href=\"<https://learning.cyverse.org/projects/dnasubway_guide/en/latest/>\"
> target=\"blank\"\>DNA Subway Manual\</a>

> \<a
> href=\"<https://learning.cyverse.org/projects/dnasubway_guide/en/latest/>\"
> target=\"blank\"\>DNA Subway Guide\</a>

> \<a href=\"<https://www.sciapps.org/>\" target=\"blank\"\>SciApps\</a>

> \<a
> href=\"<https://learning.cyverse.org/projects/sciapps_guide/en/latest/>\"
> target=\"blank\"\>SciApps Manual\</a>

> \<a
> href=\"<https://learning.cyverse.org/projects/sciapps_guide/en/latest/>\"
> target=\"blank\"\>SciApps Guide\</a>

> \<a href=\"<https://cyverse-de.github.io/api/>\"
> target=\"blank\"\>Terrain DE API Docs\</a>

> \<a href=\"<https://www.tacc.utexas.edu/tapis>\"
> target=\"blank\"\>Tapis TACC API\</a>

> \<a href=\"<http://ask.iplantcollaborative.org/questions>\"
> target=\"blank\"\>Ask CyVerse\</a>

> \<a href=\"<http://learning.cyverse.org/en/latest/>\"
> target=\"blank\"\>Agave Guide\</a>

> \<a href=\"<http://developer.agaveapi.co/#introduction>\"
> target=\"blank\"\>Agave API\</a>

> \<a href=\"<https://agaveapi.co>\" target=\"blank\"\>Agave Live
> Docs\</a>

> \<a href=\"<http://learning.cyverse.org/en/latest/>\"
> target=\"blank\"\>BisQue Guide\</a>

> \<a
> href=\"<https://learning.cyverse.org/en/latest/quick_starts.html>\"
> target=\"blank\"\>Quick Starts\</a>

> \<a
> href=\"<https://learning.cyverse.org/en/latest/tools_and_apps.html>\"
> target=\"blank\"\>Tool and App Integration Guide\</a>

> \<a href=\"<https://learning.cyverse.org/en/latest/tutorials.html>\"
> target=\"blank\"\>Tutorials\</a>

> \<a
> href=\"<https://github.com/CyVerse-learning-materials/discovery_environment_guide>\"
> target=\"blank\"\>Github Repo Link\</a>

> \<a href=\"<https://tapis-project.org/documentation/>\"
> target=\"blank\"\>TAPIS API\</a>

\_

![Home_Icon](./img/homeicon.png){width="25px" height="25px"}\_ [Learning
Center Home](http://learning.cyverse.org/)

# Managing Analyses in the Discovery Environment

An analysis is the product of a launched app that has completed its
computation of input data. The Discovery Environment maintains a history
of all your analyses, including a unique analysis ID, launch date, input
files, and other details.

------------------------------------------------------------------------

## *Browsing and Checking the Status of Analyses in the Discovery Environment*

> ::: note
> ::: title
> Note
> :::
>
> You must be logged in to manage analyses.
> :::

1\. Open the **Analyses** view by clicking on the (analyses icon) on the
left sidebar of the DE interface to monitor the status of your submitted
analysis. The analysis launched most recently will be at the top of the
list.

2\. Analyses can be sorted by Name, Start date, End date or Status. To
sort your analyses, hover your cursor over the name of the column you
wish to sort by and click on the arrow that appears beside the column
name.

> ::: note
> ::: title
> Note
> :::
>
> **Analyses Status**
>
> In the DE, an analyses can have one of the following status messages:
>
> -   **Submitted**: The analysis has been queued for running on CyVerse
>     resources.
> -   **Running**: The analyses is now running - for most apps
>     (non-interactive) the analysis will run until it is completed or a
>     time limit is reached. For interactive (VICE) applications, you
>     may now access your interactive application (check your
>     notification icon for a link or click the link-out icon ).
> -   **Completed**: The application is completed and any logs and
>     results have been written to the data store. Access the outputs by
>     clicking the folder icon ).
> -   **Canceled**: The analyses has been cancelled.
> -   **Failed**: The analyses has resulted in an error.
> :::

3\. To filter your analyses by user, click on the View dropdown menu in
the upper left corner and select either \'My analyses\' or \'Shared with
me\'. The default view is \'My analyses'.

4\. To further filter your analyses by app type, click on the Filter
dropdown menu and select the type of analyses you would like to see
(i.e., HPC, DE, VICE, or OSG).

5\. To open and view the output folder of a completed analysis, click on
the output folder icon at the right side of that particular analysis.

## *Relaunching an Analyses in the Discovery Environment*

You can relaunch an analyses to load an analyses you have previously
done. Your analyses will load with the same inputs and parameters as
previously used and you will then have the option to some, all, or none
of the of those settings.

*To relaunch*

1.  Select an analysis from your history.
2.  Click the relaunch icon ().
3.  Alter any desired parameters and launch the application.

## *Viewing Analyses Details in the Discovery Environment*

1\. Click the `Details`{.interpreted-text role="guilabel"} button or the
(info icon) to view details of the analysis (e.g. parameters used).

## *Sharing an Analyses in the Discovery Environment*

1\. Clicking the `Share`{.interpreted-text role="guilabel"} or
`Add To Bag`{.interpreted-text role="guilabel"} button to share an
analysis and its results with another CyVerse user.

## *Additional Analyses Actions in the Discovery Environment*

Clicking the `More Actions`{.interpreted-text role="guilabel"} button
allows you to perform the following actions:

-   **Go to Output folder**: View the logs and outputs of a completed
    analysis
-   **Relaunch**: Relaunch an analysis (with the option to edit
    parameters)
-   **Rename**: Rename an analysis
-   **Update Comments\...**: Add or edit comment notation on an analysis
-   **Go to analyses**: View an interactive analysis in a new tab
-   **Extend Time Limit**: Extend the time limit of an interactive
    analysis
-   **Terminate**: Stop a submitted or running analysis
-   **Delete**: Delete an analysis from your history
-   **Add to Bag**: Add to a \"bag\" for sharing

------------------------------------------------------------------------

------------------------------------------------------------------------

**Fix or improve this documentation**

-   Search for an answer:
-   Ask us for help: click on the lower right-hand side of the page
-   Report an issue or submit a change:
-   Send feedback: [learning\@CyVerse.org](learning@CyVerse.org)

------------------------------------------------------------------------