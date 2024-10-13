Getting started
===============

Starting from zero
------------------

If you start *mdnovel* by dragging a *.mdnov* file onto the icon,
that project will be opened. Otherwise, the project from the last
session will be automatically reopened, if there is one.

Let's assume that neither is the case, for example when the program
is called up for the very first time after installation.
Let's also assume that we have not yet made any preparations, i.e.
we have neither a Work-in-progress nor an outline of any kind. First
of all, we create a new empty project with **File > New > Empty project**.

A file selection dialog opens and asks for the file name and location
of the new project.

.. tip::
   It is advantageous to create a separate folder for the project, as 
   all exported documents are also stored here. This also includes 
   auxiliary files such as timelines or project-related configuration 
   files for tools and plugins. 

It is not mandatory, but we should then enter a title and the author's
name. Perhaps also a description of our idea. To get started right away,
we will postpone the remaining project settings until later.

We need at least one section in order to get space to begin writing.
And this must belong to a chapter. So we now create the first
chapter with **Chapter > Add**.

After the chapter is created, *mdnovel* sets the focus on the chapter
title entry at the top of the right pane. Let's overwrite the default
title.

.. hint::
   If you decide to have *mdnovel* `auto-number the chapters 
   <book_view.html#auto-numbering>`__, you can skip this and keep the
   default chapter title. 

There are several ways to add a section now. In this example, we
right-click on the chapter, and select **Add section**.


Starting the manuscript immediately
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

As soon as the new section appears in the tree view, we can open it
with the `section editor <editor.html>`__.


Creating a chapter structure
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you prefer to make a plan first before you start writing, *mdnovel* is
the right tool for you.
Then you first create a framework of empty chapters for which you enter content
information.
Or you can leave it at one chapter for the time being and create empty sections
in it, which you can later distribute to chapters.
The results of this preliminary work can be exported as text documents in the
form of synopses, e.g on
`chapter <chapter_menu.html#export-chapter-descriptions>`__ or
`section <section_menu.html#export-section-descriptions>`__ level.


Creating a dramatic structure
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

However, you can also start on a more abstract level and first create and
describe stages like acts or steps in order to later insert the sections as
scenes.
For this, you first create at least one chapter. Then create your stages.

The system is described on the `Plotting with mdnovel <plotting.html>`__
page.
There you also can learn how to set up multiple strands or character arcs.


-----------------


Starting with a Work-in-progress
--------------------------------

Let's assume that you have already written an extensive novel manuscript with
any text editor and now want to continue with *mdnovel*.
In this case you first make sure to set it up in a way, *mdnovel* can
recognize its parts, chapters, and sections.

.. important::
   How to set up a Work-in-progress for import
      A Work-in-progress must not have any third level heading.
      
      -  *Heading 1* → Part title.
      -  *Heading 2* → Chapter title.
      -  ``* * *`` → Section divider (not needed for the first section in a
         chapter).
      -  All other text is considered section content.
      
      All headings must be ATX style (prefixed with hashtags).


When your manuscript is ready, create your new project
with **File > New > Create from Markdown...**.

A file selection dialog opens and asks for the *Markdown* document. The new project
will be created in the same directory and named after the manuscript file, but
with the *.mdnov* extension.

.. caution::
   Once your novel is imported into *mdnovel*, your initial *Markdown* document is no
   longer needed. So if you want to keep it, you best move it elsewhere, so that
   it is not overwritten by an `exported document 
   <export_menu.html#manuscript>`__ later on. 



Starting with an outline
------------------------

Instead of a Work-in-progress, you also can import an outline made with any text editor
into *mdnovel* to get a novel project with empty, but named and described
chapters and sections.
At first glance, an outline looks the same as a Work-in-progress, but it has
third level headings for the sections, indicating their titles. If *mdnovel*
finds third-level headings, it considers all body text to be description.
In this case, formatting doesn't matter.

.. important::
   How to set up an outline for import
      An outline has at least one third level heading.
      
      -  *Heading 1* → Part title.
      -  *Heading 2* → Chapter title.
      -  *Heading 3* → Section title.
      -  All other text is considered to be chapter/section description.

      All headings must be ATX style (prefixed with hashtags).
       
When your outline is ready, create your new project
with **File > New > Create from Markdown...**.

A file selection dialog opens and asks for the *Markdown* document. The new project
will be created in the same directory and named after the outline file, but
with the *.mdnov* extension.

.. caution::
   Once your outline is imported into *mdnovel*, your initial *Markdown* document is no
   longer needed. So if you want to keep it, you best move it elsewhere, so that
   it is not overwritten by an `exported document 
   <export_menu.html#manuscript>`__ later on. 
 
   You can export and import the current outline at any time as “Descriptions” 
   separated by parts, chapters and sections.
   
   