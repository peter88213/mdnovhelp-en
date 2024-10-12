|external-link| `German <https://peter88213.github.io/mdnovhelp-de/nv_clipboard/>`_

.. |external-link| image:: ../_images/external-link.png

-----------------

============
nv_clipboard
============

**User guide**

This page refers to the latest `nv_clipboard
<https://github.com/peter88213/nv_clipboard/>`__ release.
You can open it with **Help > Collection plugin Online help**.

The plugin adds two buttons to the *mdnovel* `toolbar <../toolbar.html>`__,
and a **Clipboard Online help** entry to the **Help** menu.

.. figure:: _images/screen01.png
   :alt: mdnovel Screenshot


Installing the plugin
---------------------

- Either launch the downloaded **nv_clipboard_vx.x.x.pyzw**
  file by double-clicking (Windows/Linux desktop),
- or execute ```python nv_clipboard_vx.x.x.pyzw``` (Windows),
  resp. ```python3 nv_clipboard_vx.x.x.pyzw``` (Linux)
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


Toolbar buttons provided by the nv_clipboard plugin
---------------------------------------------------

..
   |Cut| Move the selected element from the tree to the clipboard.
   Same as ``Ctrl``-``X``. 

|Copy| Copy the selected element to the clipboard.
Same as ``Ctrl``-``C``.

|Paste| Paste the element stored in the clipboard to the tree.
Same as ``Ctrl``-``V``.

You can copy and paste the following tree elements via the system clipboard:

- Parts and chapters,
- sections,
- stages,
- plot lines,
- plot points,
- characters,
- locations,
- items,
- project notes.

.. hint::
   If multiple elements are selected, only the first one will be copied.
   However, if the element has "children", these will also be copied and pasted.

.. attention::
   Relationships are not included when copying to the clipboard.
   This also applies to the section viewpoint.   

.. |Cut| image:: _images/cut.png
.. |Copy| image:: _images/copy.png
.. |Paste| image:: _images/paste.png
