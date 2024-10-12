|external-link| `German <https://peter88213.github.io/mdnovhelp-de/nv_templates/>`__

.. |external-link| image:: ../_images/external-link.png

-----------------

============
nv_templates
============

**User guide**

This page refers to the latest `nv_templates
<https://github.com/peter88213/nv_templates/>`__ release.
You can open it with **Help > Templates plugin Online help**.


With *mdnovel*, you can define a narrative structure with stages. See
`Plotting with mdnovel <../plotting.html>`__.
*nv_templates* faciliates the reuse of narrative structures.

The plugin adds a **Story Templates** entry to the *mdnovel* **Tools** menu,
a **Create from Template...** entry to the **File > New** submenu,
and a **Template plugin Online Help** entry to the **Help** menu.

Installing the plugin
---------------------

- Either launch the downloaded **nv_templates_vx.x.x.pyzw**
  file by double-clicking (Windows/Linux desktop),
- or execute ```python nv_templates_vx.x.x.pyzw``` (Windows),
  resp. ```python3 nv_templates_vx.x.x.pyzw``` (Linux)
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


Command reference
-----------------

File > New
~~~~~~~~~~

Create from template...
^^^^^^^^^^^^^^^^^^^^^^^

This creates a new project with the narrative structure from a Markdown
template file.

-  First, a file select dialog asks for the new project’s file name
   (mdnovel v1.4+). If you cancel the dialog, you can select the file
   name later when saving the project.
-  Then a second file select dialog asks for the template file to apply.

Tools > Story Templates
~~~~~~~~~~~~~~~~~~~~~~~

Load
^^^^

This loads the narrative structure from a Markdown template file.

-  A file select dialog asks for the template file to apply.

Save
^^^^

This saves the narrative structure to a Markdown template file.

-  A file select dialog asks for the new template’s file name.

Open folder
^^^^^^^^^^^

This opens the templates folder with the OS file manager, so you can
manage and edit the templates.

Conventions
-----------

Markdown file structure
~~~~~~~~~~~~~~~~~~~~~~~

The *Story Template* Markdown file defines a narrative structure with
the help of headings and ordinary text.

First level heading for top level stages, e.g. acts
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The first level heading begins with ``#``, followed by a space and a
stage title.

Second level heading for minor stages or turning points
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The second level heading begins with ``##``, followed by a space and a
stage title.

Ordinary text
^^^^^^^^^^^^^

Any text under a heading is used as notes for the element
generated from the heading.

Example
^^^^^^^
.. highlight:: markdown

:: 

   # ACT 1

   Setup

   ## Inciting Incident

   Also called "catalyst" or "call to adventure".
   This sets the protagonist in motion.

   ## Plot Point 1

   "Point of no return": The protagonist engages with the action 
   the inciting incident has created.

   # ACT 2

   Confrontation

   ## Midpoint

   The main turning point. A significant event, changing the 
   development of things from good to bad, or vice versa.

   ## Plot Point 2

   The aftermath of the Midpoint crisis.
   What changes the protagonist from "passenger" to "driver".  

   # ACT 3

   Resolution

   ## Climax

   The final moment of the story's conflict.

This file generates the following structure in an empty project:

.. figure:: _images/structure01.png
   :alt: Screenshot


