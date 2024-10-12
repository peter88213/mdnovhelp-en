|external-link| `German <https://peter88213.github.io/mdnovhelp-de/nv_editor/>`__

.. |external-link| image:: ../_images/external-link.png

-----------------

=========
nv_editor
=========

**User guide**

This page refers to the latest `nv_editor
<https://github.com/peter88213/nv_editor/>`__ release.
You can open it with **Help > Editor plugin Online help**.

You can use the section editor to quickly edit and split individual sections.
The editor provides access to the internal markup, which is similar to HTML.

Installing the plugin
---------------------

- Either launch the downloaded **nv_editor_vx.x.x.pyzw**
  file by double-clicking (Windows/Linux desktop),
- or execute ```python nv_editor_vx.x.x.pyzw``` (Windows),
  resp. ```python3 nv_editor_vx.x.x.pyzw``` (Linux)
  on the command line.

*"x.x.x"* means the version number.

The plugin adds an **Edit** entry to the *mdnovel* **Section** menu,
and an **Editor plugin Online help** entry to the **Help** menu.


.. important::
   Many web browsers recognize the download as an executable file 
   and offer to open it immedately. 
   This starts the installation.
 
   However, depending on your security settings, your browser may 
   initially  refuse  to download the executable file. 
   In this case, your confirmation or an additional action is required. 
   If this is not possible, you have the option of downloading 
   the zip file. 


Launch the section editor
-------------------------

Open a section editor window by double-clicking on a section,
or via the **Section > Edit** menu entry when a section is selected,
or by hitting the ``Enter`` key.

.. note::

   -  If the project is locked, editor windows cannot be opened.
   -  If you choose a section already open, the window will be brought to
      the foreground.

Select text
-----------

-  Select a word via double-clicking.
-  Select a paragraph via triple-clicking.
-  Extend the selection via ``Shift``-``Arrow``.
-  Extend the selection to the next word via ``Ctrl``-``Shift``-``Arrow``.
-  ``Ctrl``-``A`` selects the whole text.

Copy/Paste text
---------------

-  ``Ctrl``-``C`` copies the selected text to the clipboard.
-  ``Ctrl``-``X`` cuts the selected text and moves it to the clipboard.
-  ``Ctrl``-``V`` pastes the clipboard text content to the cursor position.

Format text
-----------

.. role:: html(code)
   :language: html

-  ``Ctrl``-``I`` places "emphasized" markup around the selected text or at the
   cursor, like so:

   :html:`<em>Example</em>`

   If the selection is already emphasized, the command removes the markup.
-  ``Ctrl``-``B`` places "strong" markup around the selected text or at the
   cursor, like so:

   :html:`<strong>Example</strong>`

   If the selection is already strong, the command removes the markup.

-  ``Ctrl``-``M`` removes "emphasized" and "strong" markup from the selection.


Undo/Redo
---------

-  ``Ctrl``-``Z`` undoes the last editing. Multiple undo is possible.
-  ``Ctrl``-``Y`` redoes the last undo. Multiple redo is possible.

Split a section
---------------

With **File > Split at cursor position** or ``Ctrl``-``Alt``-``S``,
you can split the section at the cursor position.

-  All the text from the cursor position is cut and pasted into a newly
   created section.
-  The new section is placed after the currently edited section.
-  The new section is
   `appended <../section_view.html#append-to-previous-section>`__
   to the currently edited section.
-  The new section has the same status as the currently edited section.
-  The new section is of the same type as the currently edited section.
-  The new section has the same viewpoint character as the currently
   edited section.
-  The editor loads the newly created section.

Create a section
----------------

With **File > Create section** or ``Ctrl``-``Alt``-``N``,
you can create a section.

-  The new section is placed after the currently edited section.
-  The new section is of the same type as the currently edited section.
-  The editor loads the newly created section.

Word count
----------

-  The section word count is displayed at the status bar at the bottom
   of the window.
-  By default, word count is updated manually, either by pressing the
   ``F5`` key, or via the **Word count > Update** menu entry.
-  The word count can be updated "live", i.e. just while entering text.
   This is enabled or disabled via the **Word count > Live update** menu
   checkbox.

.. note::
   Live updating the word count is resource intensive and may slow down
   the program when editing big sections. This is why it’s disabled by
   default.


Apply changes
-------------

With ``Ctrl``-``S``,
you can apply changes to the section.
Then "Modified" status is displayed in *mdnovel*.

-  If the project is locked in *mdnovel*, you will be asked to unlock
   it before changes can be applied.

.. note::
   Before applying changes, the program checks the editor content for
   XML validity. Malformed XML will not be accepted. 


Close the editor window
-----------------------

-  To close the editor window, click on the **Close** button,
   or just close the window.
-  Under Windows you can optionally exit with **Section > Exit**
   or ``Alt``-``F4``.
-  Otherwise you can optionally exit with **Section > Quit**
   or ``Ctrl``-``Q``.
-  When closing the editor window, you will be asked for applying changes.


