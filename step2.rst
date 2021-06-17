.. include:: cyverse_rst_defined_substitutions.txtI
.. include:: custom_urls.txt


|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_


Managing Data
-------------------------

With CyVerse, you can manage data throughout the data lifecycle, from uploading, to adding metadata, to analyzing, sharing results, and making your data public for others to reuse. The DE interface is where you access, view, and manage your files in the CyVerse Data Store.

To start managing data in the Discovery Environment, you must be logged in.

Begin by clicking on the Data icon |Data Icon| in the left sidebar (you will be prompted to log in if you are not). You will see your home directory with folders first, then files listed alphabetically.

|Data window|

----

..
	#### Comment: short text description goes here ####

*Browsing Data*
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You must be logged in to browse your data.

1. To see and browse through information about your data files in the Data view, press the :guilabel:`&Customize Columns` button to select more (or fewer) columns to display, such as size, modification date, permissions, etc.

2. If the folder you're viewing has many items in it, use the < or > at the bottom of the screen to move between pages. You can also change the number of items displayed per page.

3. Click on the name of a subfolder to open that folder. As you access folders or files within your directory, breadcrumbs near the top of the page show the folder you are viewing and its parent folder(s).

4. From the top left, at the start of the breadcrumbs, you may select another root folder to view from within your home folder; clicking on the drop-down near your username will allow you to browse folders/files in "Shared With Me", "Community Data", or "Trash".


*Viewing File/Folder Details*
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Both the :guilabel:`&Details` button near the top right and the More Options menu (ellipsis) at the far right in a file or folder's row allow you to view and manage several types of information about your file/folder.

You must be logged in to view file/folder details.

1. From the Data view, click the checkbox next to a file or folder to select it and then click the :guilabel:`&Details` or the ellipsis to see specific information about the selected item, to copy the file path to the item, to add tags to the item, to edit metadata, or to set a file's info type.

2. To view your own permissions on the item and those of other users, click the 'Permissions' tab under “Details”.



*Deleting Files/Folders*
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You must be logged in to delete files/folders.

1. From the Data view, select the desired file/folder by clicking the checkbox to its left. You can select multiple files/folders. To unselect an individual file/folder, click the checkbox again. To select (or unselect) all files/folders, click the checkbox at the top of the list.

2. Click on the More Options menu (ellipsis) in the upper right corner of the Data view and select **Delete** from the pop-up menu. When the file has been fully deleted, you will receive an automated notification under the notification icon |notification|. When deleting or moving a file/folder, you must receive the completion notification before you can change anything associated with that file/folder.


   .. tip:: Deleted files can be retrieved from your Trash. To access your Trash folder, click on your username in the top left corner of the Data view.



*Uploading/Importing Small Files*
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can upload smaller files (<2GB) using the DE interface. For larger files or large numbers of files, using methods such as Cyberduck or iCommands is faster and recommended. See the documentation for those tools in our |Data Store Guide|.

You must be logged in to upload/import files.

1. Click the **Data** button |Data Icon| in the Discovery Environment’s left sidebar to access the Data view.

2. The Data view shows a directory of the files and folders in your Data Store. You can select an existing folder as the destination for your uploaded file(s) or click the **Folder** button to create a new folder. If you do not select a destination, the default file destination is your home Data Store folder (i.e., iplant/home/CYVERSE_USERNAME).

3. Click the **Upload** button |upload button| to choose your options for importing files into the Data Store:

    - To upload files from your local computer, choose **Browse Local**; a file browser will open and you may select files to upload.

    - To upload files from a URL, choose **Import by URL**; you may paste in a valid HTTP or an FTP URL, then click **Import**. You may paste additional URLs or close this window by clicking **Done**.


  .. tip::


    When your Data Store file browser is open, you can also upload files from your computer by dragging them into your browser window.


    |upload drag|



4. When you have begun the upload, you will get an automated notification that the file(s) has been queued. To view the status of an upload or import,  go click the **Upload** button and choose **View Upload Queue**.


   |upload queue|


   .. Note::


     The queue will only display the status of uploads from local files. Files imported by URL will generate an automated notification (bell icon, upper-right) upon completion or failure to upload.



*Advanced Features*
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


The Discovery Environment also supports advanced data management tasks such as organizing your datasets, associating data with metadata, requesting a Digital Object Identifier (DOI), and importing or submitting data to/from NCBI SRA. For how-to information on these advanced features, see our Quick Start Guides <https://learning.cyverse.org/en/latest/quick_starts.html> and our Tutorials <https://learning.cyverse.org/en/latest/tutorials.html>.




..
	#### Comment: Suggested style guide:
	1. Steps begin with a verb or preposition: Click on... OR Under the "Results Menu"
	2. Locations of files listed parenthetically, separated by carets, ultimate object in bold
	(Username > analyses > *output*)
	3. Buttons and/or keywords in bold: Click on **Apps** OR select **Arabidopsis**
	4. Primary menu titles in double quotes: Under "Input" choose...
	5. Secondary menu titles or headers in single quotes: For the 'Select Input' option choose...
	####


----

**Fix or improve this documentation:**

- On Github: `Repo link <https://github.com/CyVerse-learning-materials/discovery_environment_guide>`_
- Send feedback: `Tutorials@CyVerse.org <Tutorials@CyVerse.org>`_


----

.. |CyVerse logo| image:: ./img/cyverse_rgb.png
    :width: 500
    :height: 100
.. _CyVerse logo: http://learning.cyverse.org/
.. |Home_Icon| image:: ./img/homeicon.png
    :width: 25
    :height: 25
.. _Home_Icon: http://learning.cyverse.org/
.. |data_icon| image:: ./img/de/data_icon.png
    :width: 30
    :height: 30
.. |data_window| image:: ./img/de/data_window.png
    :width: 550
    :height: 300
.. |viewing_window| image:: ./img/de/viewing_window.png
    :width: 400
    :height: 200
.. |data_links_window| image:: ./img/de/manage_data_links.png
    :width: 450
    :height: 250
.. |delete_icon| image:: ./img/de/delete_icon.png
    :width: 15
    :height: 15
.. |link_icon| image:: ./img/de/link_icon.png
    :width: 15
    :height: 15
.. |manage_sharing| image:: ./img/de/manage_sharing_menu.png
    :width: 400
    :height: 300
.. |discovery environment| raw:: html

    <a href="https://de.cyverse.org/de/" target="_blank">https://de.cyverse.org/de/</a>
