Preparations
============

Setting up mdnovel
------------------

If *mdnovel* were a commercial application, all the
steps described below would be performed automatically
by the setup program. On Windows, for instance, this would
then be an *.exe* or *.msi* file that must be executed
with special authorizations and may even require a costly
certificate in order to be approved for download and
installation.

There is also the problem that a separate setup program would
have to be created and maintained for each operating system.
For Linux, it would be necessary to provide installation
packages or images, whereby there are a multitude of different
standards.

Because I don't run a software business, but am just a
hobbyist and rather want to write novels, I've decided to
go a different route: I provide an executable Python zip archive
that works the same way on all operating systems
if Python is installed correctly.
No Internet connection is required to install and operate *mdnovel*.

The very last setup steps, which vary depending
on the operating system and may also require special authorizations,
must be carried out by the intrepid users themselves.
I do what I can to make these steps easier, and provide
detailed instructions for Windows below.
Enjoy!

Installing the application
~~~~~~~~~~~~~~~~~~~~~~~~~~

Step 1
   - Either launch the downloaded **mdnovel_vx.x.x.pyzw**
     file by double-clicking (Windows/Linux desktop),
   - or execute

     ```python mdnovel_vx.x.x.pyzw``` (Windows), resp.

     ```python3 mdnovel_vx.x.x.pyzw``` (Linux) on the command line.

   *"x.x.x"* means the version number.

   In both cases, a pop-up window should appear indicating
   that the installation was successful.

   .. important::
      Many web browsers recognize the download as an executable file 
      and offer to open it immedately. 
      This starts the installation.
    
      However, depending on your security settings, your browser may 
      initially  refuse  to download the executable file. 
      In this case, your confirmation or an additional action is required. 
      If this is not possible, you have the option of downloading 
      the zip file. 


Making mdnovel accessible on the Desktop
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. admonition:: Note for Linux users

   In the following chapters, the Windows procedure is described. 
   
   As a Linux user, you are expected to know how to set up 
   a program launcher on your specific desktop. 
   Roughly speaking, it is a matter of calling **python3** 
   with **~/.mdnov/run.pyw** and an optionally specified 
   file as parameters. 
   
   With the XFCE desktop, for example, my launcher command is:
   
   ``python3 /home/peter/.mdnov/run.pyw %F``
   
   You might have to copy the *mdnovel* icons to a dedicated image 
   directory where your program launcher gets the icons from. 
   You also may want to set *mdnovel* as standard application for
   files with the *.mdnov* extension, and assign them the *mdnovel*
   logo as file icon. 
   With the XFCE desktop, none of this was too difficult for me.
   In doubt, refer to your desktop documentation. 
   

Step 2
   Open the installation folder.

Step 3
   Drag and drop **run.pyw** to the desktop while holding
   down the ``Alt`` key. This creates a shortcut to launch
   *mdnovel* from the Windows desktop. Now you can also
   drag and drop *.mdnov* project files to this shortcut.

Step 4
   Optionally, you can replace the "Python" icon with the
   *mdnovel* logo you may find in the installation's
   *icons* subdirectory.

   To do this, right-click on the desktop shortcut and
   open the **Properties** dialog. Select the **Shortcut**
   Tab and click on the **Change icon** button (1). In the
   icon selection dialog, click on the **Browse...** button
   (2). This opens a file selection dialog. Move to
   ``<home>\.mdnov\icons`` and double-click on the "N" logo
   (3).

Step 5
   To rename the shortcut to *mdnovel*, right-click on
   the desktop shortcut and open the **Properties**
   dialog. In the first tab, replace "Shortcut to run.pyw"
   with "mdnovel".




Updating the application
~~~~~~~~~~~~~~~~~~~~~~~~

Just execute the first step as described above.
If there is any further action required, the setup script will
give you a message.

