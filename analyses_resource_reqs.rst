|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_


Analysis Resource Requests
--------------------------

In an App Launch dialog,
"Resource Requirement" panels will always be appended as the last step in the dialog,
after the analysis name, details, and parameter group panels defined by that app.

If required, the user may adjust these minimum resource requirements
so that the analysis may be submitted with requests for larger minimum resources.
Note that this may cause those analyses to wait longer in the submission queue
until a node that matches those minimum requirements becomes available.
So generally users may wish to leave the resource requests set to the defaults
that the tool or app integrator has set.

----

**Single Step Apps**

If there is only 1 step in the analysis,
then one "Resource Requirements" panel will be appended to the App Launch dialog.
|single_step_reqs|

**Workflows**

If there is more than 1 step in the analysis,
then each step in the workflow will append its own "Resource Requirements" panel.
|workflow_reqs|

**Resource Limits**

The drop-downs for each requirement are populated with the same values available to tool integrators in the DE's add/edit private tool dialog.

* 0,1,2,4,8 minimum CPU
* 0,2,4,8,16 GiB minimum memory
* 0,1,2,4,8, and doubling each additional step up to 512GiB minimum disk space

If a step defines minimum CPU, RAM, or disk requirements,
those values will be populated by default in that step's "Resource Requirements" panel.
Additionally, min and max values set for these resources are used to limit which options are available in that resource's drop-down.

For example, the following tool has 3.4 min CPU, 4GiB max memory, and 4GiB min disk space defined.
So the "Resource Requirements" panel in the launch dialog for an app using this tool will set 3.4 min CPU cores and 4GiB min disk space by default.
|resource_limits|

Additionally, if the user wishes to adjust the minimum CPU requirements,
then only the options 0, 4, and 8 will be available.
Similarly for memory, only 0, 2, and 4GiB options will be available;
and for disk, the options for 1 and 2 GiB will not be available
(since those are below the 4GiB minimum defined by the tool).

Selecting a '0' in any of these drop-downs has the effect of requesting no requirement for that resource in the analysis submission.

**VICE Limits**

As another example, our internal docs for creating VICE tools used to instruct admins to use
0.1 min CPUs, 2 max CPUs, and 4,000,000,000 max memory.
So the "Resource Requirements" panel for the following "jupyter-lab" app
will use 0.1 min CPUs by default, and limit the CPU options to 0, 1, or 2 CPUs.
Minimum memory will not be auto-filled by default,
but will be limited to only 0 or 2GiB for the user,
since the 4,000,000,000 max memory limit is just less than the next 4GiB option.
|vice_limits|

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
    :width: 15
    :height: 15
.. _Home_Icon: http://learning.cyverse.org/

.. |single_step_reqs| image:: ./img/de/analyses_resource_reqs/1_single_step.png
    :width: 475
    :height: 275

.. |workflow_reqs| image:: ./img/de/analyses_resource_reqs/2_workflow.png
    :width: 475
    :height: 275

.. |resource_limits| image:: ./img/de/analyses_resource_reqs/3_limits.png
    :width: 475
    :height: 278

.. |vice_limits| image:: ./img/de/analyses_resource_reqs/4_vice_limits.png
    :width: 475
    :height: 275
