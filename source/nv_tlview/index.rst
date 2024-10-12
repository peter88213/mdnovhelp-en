|external-link| `German <https://peter88213.github.io/mdnovhelp-de/nv_tlview/>`_

.. |external-link| image:: ../_images/external-link.png

-----------------

=========
nv_tlview
=========

**User guide**

This page refers to the latest `nv_tlview
<https://github.com/peter88213/nv_tlview/>`__ release.
You can open it with **Help > Timeline view Online help** or with ``F1``.

*nv_tlview* is a plugin providing a timeline view with sections
that are given a narrative date/day and time.

The plugin adds a **Timeline view** entry to the *mdnovel* **Tools** menu,
and a **Timeline view Online help** entry to the **Help** menu.
The Toolbar gets a |Timeline| button.

.. |Timeline| image:: _images/tlview.png

.. figure:: _images/screen01.png
   :alt: mdnovel Screenshot


Installing the plugin
---------------------

- Either launch the downloaded **nv_tlview_vx.x.x.pyzw**
  file by double-clicking (Windows/Linux desktop),
- or execute ```python nv_tlview_vx.x.x.pyzw``` (Windows),
  resp. ```python3 nv_tlview_vx.x.x.pyzw``` (Linux)
  on the command line.

*"x.x.x"* means the version number.


.. important::
   Many web browsers recognize the download as an executable file 
   and offer to open it immedately. 
   This starts the installation.
 
   However, depending on your security settings, your browser may 
   initially  refuse  to download the executable file. 
   In this case, your confirmation or an additional action is required. 
   If this is not possible, you have the option of downloading 
   the zip file. 


Operation
---------


Start the Timeline view
~~~~~~~~~~~~~~~~~~~~~~~

- Open the Timeline view either from the main menu: **Tools > Timeline view**,
- or via the |Timeline| button in the toolbar.


Mouse scrolling
~~~~~~~~~~~~~~~

- Scroll the timeline horizontally with ``Shift``-``Mousewheel``.
- Scroll the timeline vertically with the mousewheel.
- Scroll the timeline in any direction by right-clicking on the canvas and dragging the mouse.
- Increase or reduce the time scale with ``Ctrl``-``Mousewheel``.
- Change the distance limits for stacking with ``Shift``-``Ctrl``-``Mousewheel``.


Selecting a section in the *mdnovel* project tree
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Select a section by double klicking on a timeline marker.
  This will bring the *mdnovel* application window in the foreground.


Shifting a section in time
~~~~~~~~~~~~~~~~~~~~~~~~~~

- Hold down the ``Shift`` button and click on the timeline marker,
  then drag it with the mouse.
  This will move the section forward or backward in time
  while keeping the duration.


Shifting the section end
~~~~~~~~~~~~~~~~~~~~~~~~

- Hold down the ``Ctrl`` and ``Shift`` buttons and click on the timeline marker,
  then drag it with the mouse.
  This will increase or decrease the section's duration
  while keeping the start date/time.


.. hint::
   - Shifting operations with the mouse can be aborted
     with the ``Esc`` key before releasing the mouse button.
   - Shifting operations with the mouse can be undone 
     with ``Ctrl``-``Z`` or |undo|. 

Command reference
-----------------


"Go to" menu
~~~~~~~~~~~~

First event
   Shift the timeline so that the earliest event
   is positioned near the left edge of the window.

Last event
   Shift the timeline so that the latest event
   is positioned near the right edge of the window.

Selected section
   Shift the timeline so that the section selected in the *mdnovel* project tree
   is positioned in the center of the window.


"Scale" menu
~~~~~~~~~~~~

Hours
   This sets the scale to one hour per line.

Days
   This sets the scale to one day per line.

Years
   This sets the scale to one year per line.

Fit to window
   This sets the scale and moves the timeline, so that all sections with
   valid or substituted date/time information fit into the window.


"Substitutions" menu
~~~~~~~~~~~~~~~~~~~~

Use 00:00 for missing times
   - If ticked, "00:00" is used as display time for sections without time information.
     This does not affect the section properties.
   - If unticked, sections without time information are not displayed.


"Cascading" menu
~~~~~~~~~~~~~~~~

The section marks are stacked on the timeline canvas, so that they would not
overlap or cover the title of previous sections.
If the stacking algorithm does not seem good enough to you,
you can adjust its limits.

Tight
   Arrange consecutive events behind each other, even if they are close together.

Relaxed
   Arrange consecutive events in a stack, even if they are some distance apart.

Standard
   Reset the cascading to default.

.. hint::
   You can fine-tune the stacking limits with ``Shift``-``Ctrl``-``Mousewheel``.



"Help" menu
~~~~~~~~~~~

Online help
   Open this help page in a web browser.
   Same as ``F1``.


Buttons in the footer toolbar
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

|rewindLeft| Go one page back
   Shift the timeline to go about one screen width back in time.
   Same as the "back" mouse button (Windows).

|arrowLeft| Scroll back
   Shift the timeline to go 1/5 screen width back in time.
   You can move it more precisely with the mouse wheel.

|goToFirst| Go to the first event
   Shift the timeline so that the earliest event
   is positioned near the left edge of the window.

|goToSelected| Go to the selected section
   Shift the timeline so that the section selected in the *mdnovel* project tree
   is positioned in the center of the window.

|goToLast| Go to the last event
   Shift the timeline so that the latest event
   is positioned near the right edge of the window.

|arrowRight| Scroll forward
   Shift the timeline to go 1/5 screen width forward in time.
   You can move it more precisely with the mouse wheel.

|rewindRight| Go one page forward
   Shift the timeline to go about one screen width forward in time.
   Same as the "forward" mouse button (Windows).

|arrowDown| Reduce the time scale
   Reduce the time scale in major steps.
   Fine scaling is meant to be done with the mouse wheel.

|fitToWindow| Fit to window
   This sets the scale and moves the timeline, so that all sections with
   valid or substituted date/time information fit into the window.

|arrowUp| Increase the time scale
   Increase the time scale in major steps.
   Fine scaling is meant to be done with the mouse wheel.

|undo| Undo the last change
   This restores date/time/duration
   before the last mouse operation on a section.
   Same as ``Ctrl``-``Z``

   .. caution::   
      Interim changes to date/time/duration on the same section
      via the section properties in *mdnovel*
      may get lost. 
      
Close
   Close the timeline viewer window.
   Same as ``Ctrl``-``Q`` (Linux)
   or ``Alt``-``F4`` (Windows).


.. |rewindLeft| image:: _images/rewindLeft.png
.. |arrowLeft| image:: _images/arrowLeft.png
.. |goToFirst| image:: _images/goToFirst.png
.. |goToLast| image:: _images/goToLast.png
.. |arrowRight| image:: _images/arrowRight.png
.. |rewindRight| image:: _images/rewindRight.png
.. |goToSelected| image:: _images/goToSelected.png
.. |arrowDown| image:: _images/arrowDown.png
.. |fitToWindow| image:: _images/fitToWindow.png
.. |arrowUp| image:: _images/arrowUp.png
.. |undo| image:: _images/undo.png

