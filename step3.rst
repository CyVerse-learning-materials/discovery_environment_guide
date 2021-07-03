.. include:: cyverse_rst_defined_substitutions.txt
.. include:: custom_urls.txt

|CyVerse_logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_


Using Apps in the Discovery Environment
----------------------------------------

You can select from several hundred applications (apps) available in the Discovery Environment when you are ready to analyze your data.


.. tip::

	When launching an app, you can log out or navigate to another page or operation after you start the task; an automated email notification is sent to you when those tasks are completed.

*Browsing Apps in the Discovery Envirorment*
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You must be logged in to browse and use apps.

1. Click |apps icon| in the left sidebar of the DE to see the Apps view. When
you first access the Apps view, you may be prompted to log in. After logging
in, you will see a screen that looks something like this:


|apps page|


*Sorting and Filtering Apps in the Discovery Environment*
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

To sort the list of apps in ascending or descending order by app name, the name of the person who integrated the app in CyVerse, or its average rating, click on the column headings.

You can navigate between pages and change how many apps are listed on a page by using the < or > controls at the bottom of the page.

By default, the Apps view displays all apps that are available to you. With hundreds of apps and sometimes many versions of an app in the DE, you may want to view a subset of all available apps. There are two ways to do this. First, in the upper left corner of the Apps view, the currently active subset of apps is shown as the primary filter. Click the drop-down arrow next to the currently active subset to select a different apps subset to display:


The currently selected app subset is highlighted in gray. The available app subsets are:



.. list-table::
    :header-rows: 1


    * - Application type
      - Description
    * - Apps under development
      - Apps that you have added to the DE that have not been made public
    * - Favorite apps
      - Apps that you have marked as favorite apps in the DE
    * - My public apps
      - Apps that you have added to the DE that have been made publicly
        available
    * - Shared with me
      - Apps that other users have shared with you
    * - High-Performance Computing
      - Apps that run at the Texas Advanced Computing Center using the |TAPIS
        API|
    * - Browse All Apps
      - All apps available to you in the DE


You can further reduce the list of the apps displayed by selecting a filter.
Click the drop-down arrow in the Filter control (upper right corner of the Apps
view) to select the type of apps you'd like to see in the listing:


The currently selected filter is displayed in the Filter control itself. If no
filter is selected, the control will be empty. The currently available app
filters are:



.. list-table::
    :header-rows: 1


    * - Application filter
      - Description
    * - HPC
      - High Performance Computing apps that run using the |TAPIS
        API| (formerly known as Agave)
    * - DE
      - Executable (non-interactive apps) that run on CyVerse computing
        resources
    * - VICE (formerly Interactive)
      - Interactive apps (e.g., Jupyter, RStudio, R Shiny) and other apps with
        their own interactive interfaces
    * - Open Science Grid (OSG)
      - Executable (non-interactive apps) that run on OSG
        resources

The app filter you selected will be displayed in the Filter control.
To dismiss a filter, click the `X` to the right of the filter name.

*Viewing App Details in the Discovery Environment*
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


When you've found an app of interest, select it by clicking the checkbox to the
left of the app name. A *Details* button will appear in the upper right corner
of the Apps view, just to the right of the Filter control.

Click the Details button to see additional information about the app (e.g.,
description, number of times run, etc.).


The Details panel has several controls available. Click the Heart icon to add
that app to your list of favorite apps (to remove from your favorite list,
click the heart again). The heart will be solid blue if the app is already on
your list of favorites. Click the Link icon to display a link to the app that
you can copy and share with other CyVerse users. The Stars icon labeled
:guilabel:`Your rating` allows you to rate the app. The :guilabel:`Tools used by this App` tab contains information about the underlying tools (steps) the
app uses to perform an analysis. To dismiss the App Details view, click
anywhere outside the panel.

 ..  tip::

     Favorite your frequently used apps to make them easier to find.




*About VICE Apps in the Discovery Environment*
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


One type of app that you can filter for in the Discovery Environment is VICE apps (VICE stands for Visual Interactive Computing Environment and is a part of the Discovery Environment). VICE apps are executable apps that run as workflows on high performance or high throughput computing environments and include a Graphical User Interface (GUI) or an Integrated Development Environment (IDE) such as Project Jupyter, RStudio, or remote desktops to the DE.


You must request access and be approved to use VICE apps through the CyVerse User Portal |CyVerse User Portal|.



*Advanced Features in the Discovery Environment*
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


The Discovery Environment also supports advanced features for apps such as
integrating different types of apps into the DE, creating and running
containers, and using Application Programming Interfaces (APIs) for
programmatic backend access to CyVerse services. For how-to information on
these features, see our |Quick Starts|, |Tool and App Integration Guide|, and
our |Tutorials|.


----

**Fix or improve this documentation**

- Search for an answer:
  |CyVerse Learning Center|
- Ask us for help:
  click |Intercom| on the lower right-hand side of the page
- Report an issue or submit a change:
  |Github Repo Link|
- Send feedback: `Tutorials@CyVerse.org <Tutorials@CyVerse.org>`_



----

.. |CyVerse logo| image:: ./img/cyverse_rgb.png
    :width: 500
    :height: 100
.. _CyVerse logo: http://learning.cyverse.org/
.. |Home_Icon| image:: ./img/homeicon.png
    :width: 15
    :height: 15
.. _Home_Icon: http://learning.cyverse.org/
.. |info| image:: ./img/de/info.png
    :width: 15
    :height: 15
.. |comment| image:: ./img/de/comment.png
      :width: 15
      :height: 15
.. |favorite| image:: ./img/de/favorite.png
      :width: 15
      :height: 15
.. |rating| image:: ./img/de/rating.png
      :width: 70
      :height: 15
.. |Unavailable| image:: ./img/de/unavailable.png
      :width: 15
      :height: 15
.. |beta| image:: ./img/de/beta.png
      :width: 15
      :height: 15
.. |private| image:: ./img/de/private.png
      :width: 15
      :height: 15
.. |dots| image:: ./img/de/dots.png
      :width: 15
      :height: 20
.. |de_app_icon| image:: ./img/de/de_app_icon.png
      :width: 250
      :height: 100
.. |apps_icon| image:: ./img/de/apps_icon.png
    :width: 30
    :height: 30
.. |muscle_app_window| image:: ./img/de/muscle_app_window.png
    :width: 425
    :height: 250
.. |discovery environment| raw:: html

    <a href="https://de.cyverse.org/de/" target="_blank">https://de.cyverse.org/de/</a>

.. |muscle| raw:: html

    <a href="https://de.cyverse.org/de/?type=apps&app-id=9b41c9e4-5031-4a49-b1cb-c471335df16e&system-id=de" target="_blank">Muscle 3.8.31</a>

.. |de sample plants| raw:: html

    <a href="https://de.cyverse.org/de/?type=data&folder=/iplant/home/shared/cyverse_training/platform_guides/discovery_environment/muscle_3_8_31/01_muscle_input" target="_blank">DE_sample_plants.fas</a>
