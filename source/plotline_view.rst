Plot line properties
====================

The Plot line properties view opens in the right pane when you
select a `plot line <plotting.html#defining-plot-lines>`__ in the tree.


Title and description
---------------------

Title and description are displayed in an editable "index card".

The editing of the title can be completed by pressing the ``Enter`` key.
Changes to the description are applied when the mouse is clicked
anywhere outside the text input field.


Short name
----------

Be sure to enter a short name to be displayed as a reference in the tree.
A single character like "A", "B", "C" is recommended.

.. figure:: _images/plotline_view02.png
   :alt: mdnovel screenshot

   Example: Plot line short names as displayed in the tree


Section assignments
-------------------

The number of sections that belong to the selected plot line is shown
below the "Short name" entry. The assignments can be made in the
`section properties view <section_view.html#plot>`__.
You can unlink all sections from the selected plot line at once by
clicking on the **Clear section assignments** button.

.. hint::
   A convenient way to manage and keep track of section assignments is 
   offered by the `matrix view <matrix.html>`__. 


Links
-----

Expand or collapse this frame by clicking on the label.

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
      ``.mdnovel/config`` directory (where all configuration files are stored).
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

When the "sticky note" of a plot line contains text, "N" is
displayed in the tree view as a reminder. If the branch of a
plot line with plot points containing notes is collapsed,
the "N" is displayed in the plot line row.

.. note::
   The "sticky notes" are only for working with *mdnovel*.
   They are not meant to be exported into a document.


Navigation buttons
------------------

- **Previous** moves the selection to the previous plot line in the tree.
- **Next** moves the selection to the next plot line in the tree.

