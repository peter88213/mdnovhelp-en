Plot menu
=========

**Plot elements operation**


Add Plot line
-------------

**Add a new plot line to the story**

With **Plot > Add plot line**,
you can add a project note to the tree.

-  If a plot line is selected, the new plot line is placed after the selected one.
-  Otherwise, the new plot line is placed at the last position.
-  The new plot line has an auto-generated title. You can change it in the
   right pane.


Add Plot point
--------------

**Add a new Plot point to the selected plot line**

With **Plot > Add Plot point**,
you can add a plot point to a plot line.

- If a plot point is selected, the new plot point is placed after the selected one.
- If a plot line is selected, the new plot point is placed at the last position.
- Otherwise, no new plot point is generated.
- The new plot point has an auto-generated title. You can change it in
  the right pane.


Insert Stage
------------

**Insert a stage between the sections**

With **Plot > Insert Stage**,
you can insert a stage after the selected chapter or section.

.. hint::
   By default, the new stage is on the second level. 
   You can change the level to first (see below).


Change Level
------------

**Change the level of the selected stages**

With **Plot > Change Level**,
you can change the level of the selected stages.


-  **1st Level** is displayed in bold face.
-  **2nd Level** is displayed in regular font.

.. note::
   The stage level is only for visual distinction. It has no
   influence on the program functions. 


Export plot grid
----------------

**Export a CSV document**

With **Plot > Export plot grid**,
you can create a CSV file as described in the
`Plotting with mdnovel <plotting.html#plot-grid>`__ chapter,
with a row per section, containing the following data:

- The sequential section number as a hyperlink to the section in the
  manuscript (if any)
- Narrative date
- Narrative time
- Day
- Section title
- Section description
- Viewpoint character
- One column per plot line with the section's plot line notes
- Tags
- Scene
- Goal/Reaction/(custom)
- Conflict/Dilemma/(custom)
- Outcome/Decision/(custom)
- Section notes

.. note::
   Only "normal" sections appear in the plot grid. 
   Sections of the "Unused" type are omitted.

File name suffix is ``_grid``.


Export story structure description
----------------------------------

**Export a Markdown-formatted document**

With **Plot > Export story structure description**,
you can create a text document that contains
all stages, each with description.
File name suffix is ``_structure``.

.. hint::
   This is also a full synopsis, with the emphasis on the dramaturgical structure.


Export plot line descriptions
-----------------------------

**Export a Markdown-formatted document**

With **Plot > Export plot Export plot line descriptions**,
you can create a text document that contains
stages, plot lines, and plot points, each with description.
The plot points are linked to the manuscript and to the section descriptions.
File name suffix is ``_plotlines``.


Show Plot list
--------------

**Show an HTML report with plot elements**

With **Plot > Show Plot list**,
You can create a list-formatted HTML file that contains
a plot list similar to the ODS plot list (see above),
but without any hyperlinks,
and launch your system’s web browser for displaying it.

.. figure:: _images/plot_menu03.jpg
   :alt: Edge browser screenshot

   Edge browser screenshot

.. note::
   The report is a temporary file, auto-deleted on program exit.
   If needed, you can have your web browser save or print it.

