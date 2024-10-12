Character properties
====================

The Character properties view opens in the right pane when you
select a character in the tree.


.. figure:: _images/character_view01.png
   :alt: Screenshot

Title and description
---------------------

Title and description are displayed in an editable "index card".

The editing of the title can be completed by pressing the ``Enter`` key.
Changes to the description are applied when the mouse is clicked
anywhere outside the text input field.

Full name
---------

The character's title as shown on the index card is used as
a short name at several places. The full name can be entered
separately. Editing can be completed by pressing the ``Enter`` key.

AKA
---

This entry field is for alias names. Editing can be completed
by pressing the ``Enter`` key.

Tags
----

Tags are a very freely usable tool for labeling characters in the
tree view. Tags do not have to be defined elsewhere, but simply
entered in the input field separated by semicolons.
Editing can be completed by pressing the ``Enter`` key.

.. caution::
   If you want to use a tag more than once, make sure you use 
   the same spelling in the different places. 

Bio
---

Expand or collapse this frame by clicking on the label.

.. figure:: _images/character_view02.png
   :alt: Screenshot

Birth/death date
   Format: *YYYY-MM-DD*, according to ISO 8601.

The editing of the birth and death dates can be completed by pressing the
``Enter`` key. Changes to the bio are applied when the mouse is
clicked anywhere outside the text input field.


Goals
-----

Expand or collapse this frame by clicking on the label.

.. figure:: _images/character_view03.png
   :alt: Screenshot

Changes to the goals are applied when the mouse is clicked anywhere outside
the text input field.

.. hint::
   This text box can hold any character data that seem important to you.
   If "Goals" is not the right category for you, you can change the label
   in the `book settings <book_view.html#renamings>`__. 


Links
-----

Expand or collapse this frame by clicking on the label.

.. figure:: _images/character_view04.png
   :alt: Screenshot
   
This is a list for image and research document links.

Although *mdnovel* holds some character/location/item data, it is
not the right application for extensive world building. For this,
you may want to use more powerful software, like `Zim Desktop Wiki
<https://zim-wiki.org/>`__. In this case, *mdnovel* allows you to
create links to the text files that will take you quickly to the right
places in the wiki.

Or you have collected some images that could inspire you when writing.
Then simply create links to these images to open them with your
system's standard image viewer.

.. tip::
   If you have collected several images for a character in a folder 
   that your standard image viewer can browse through, a single link 
   to any image file is sufficient.  
   
The links are displayed in a list in the order they are entered.

Add Link
   When clicking on |Add|, a file selection dialog opens. The selected
   file will be added to the link list.

   .. hint::
      By default, the dialog shows image files. For other file types, 
      change the selector in the lower right corner. 
      
      .. figure:: _images/filePicker01.png
         :alt: Screenshot
         
         Windows Explorer Screenshot


Remove Link
   When clicking on |Remove| or pressing the ``Del`` key,
   the selected link is removed from the list.

Open Link
   When double-clicking on a link, or clicking on |Goto|,
   the link is opened with the standard application for the link's file type.

   .. hint::
      If you want to open certain linked files with another application than the 
      standard application, you can provide a *mdnovel* "launcher" setting. 
      For this, just create a text file named **launchers.ini** in the 
      ``.novx/config``  directory (where all configuration files are stored).
      Here you can assign applications to the file extensions.
      
      Zim desktop wiki pages are a special case. 
      For this, the Zim program is assigned to the `.zim` extension. 
      
      This example shows a setting that makes *mdnovel* open text files
      with the *Zim Desktop Wiki* application instead of the standard text 
      editor: 
      
      ::
     
         [SETTINGS]
         .zim = C:/Program Files (x86)/Zim Desktop Wiki/zim.exe 
         
      .. figure:: _images/launchers.png
         :alt: Screenshot
         
         Windows Explorer Screenshot

.. |Add| image:: _images/add.png
.. |Goto| image:: _images/goto.png
.. |Remove| image:: _images/remove.png


"Sticky note"
-------------

The yellow text area is for notes. Changes are applied
when the mouse is clicked anywhere outside the text input field.

When the "sticky note" of a character contains text, "N" is
displayed in the tree view as a reminder.

.. note::
   The "sticky notes" are only for working with *mdnovel*.
   They are not meant to be exported into a document.
   However, they appear in the `character list`_.

.. _character list: characters_menu.html#export-character-list-spreadsheet


Navigation buttons
------------------

- **Previous** moves the selection to the previous character in the tree.
- **Next** moves the selection to the next character in the tree.
