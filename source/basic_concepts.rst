Basic concepts
==============


The Book hierarchy
------------------

Parts
~~~~~

A novel is expected to be divided into chapters and sections. Parts
are optional; technically they are first level chapters.
However, in the *mdnovel* project tree they are on the same
level as the chapters, but they produce a heading one level above.
Thus, parts are mainly for inserting first level headings between the
chapters, if needed.

.. hint::
   You can convert chapters into parts and vice versa by simply 
   `changing the level <tree_context_menu.html#change-level>`__.


Chapters
~~~~~~~~

A *mdnovel* project must at least have one chapter. In the exported
documents, regular chapters have a second level heading.

For *mdnovel*, the chapters only serve as containers for sections
to which the actual dramaturgical function is assigned.
This is why there are only a few `chapter properties <chapter_view.html>`__
to be set.


Sections
~~~~~~~~

All body text of a novel in *mdnovel* belongs to sections.
Sections can be scenes, pieces of exposition, descriptions, narrative
summaries---it is entirely up to you how you divide your text into
sections. There is a variety of `metadata for sections
<section_view.html>`__ for your free use.

In the text body of the exported documents, sections are separated by
section dividers by default, like so:

``* * *``

However, if you need more fragmented sections when plotting and organizing
than the reader should see later, you can also `append sections
<section_view.html#append-to-previous-section>`__ to each
other as new paragraphs with no section divider inbetween.


Part/chapter/section types
--------------------------

Each part, chapter, and section is of a type that can be changed via
context menu or Part/Chapter/Section menu. The type can be *Normal* or
*Unused*.

Normal
   -  "Normal" type parts, chapters, and sections are counted. The totals
      are displayed in the status bar.
   -  "Normal" type sections are exported to the manuscript and included in
      the word count.
   -  "Normal" type parts and chapters can have subelements of each type.
   -  "Normal" type tree elements are color coded according to the
      `coloring mode settings <view_menu.html#coloring-mode>`__.

Unused
   You can mark parts, chapters, and sections as unused to exclude them
   from word count totals and export.

   -  The subelements of unused parts and chapters are unused as well.
   -  If you mark a section "Unused", its properties are preserved.
   -  Unused tree elements are displayed in gray.


Section completion status
-------------------------

You can assign a status to each "Normal" type section via context menu
or Section menu.
You can choose between *Outline*, *Draft*, *1st Edit*, *2nd Edit*,
and *Done*.

-  You can choose a `coloring mode <view_menu.html#coloring-mode>`__
   to display sections in different colors depending on their
   completion status.
-  Optionally, you can declare one of the status to be the current
   `work phase <book_view.html#writing-progress>`__,
   and choose a `coloring mode <view_menu.html#coloring-mode>`__
   that highlights sections that are behind schedule.
-  Newly created sections are set to "Outline" by default.
-  Word counts by status appear in the `Book properties
   <book_view.html#writing-pogress>`__.


-----------------


Characters and story world
--------------------------

You can define characters, locations, and items, and you can relate
them to sections to keep track of their place in the story.
There is also some metadata stored with *mdnovel*, mainly as a
quick reference that might come in handy when writing or editing.

.. note::
   *mdnovel* is not meant as a tool for extensive world building. 
   For this, there is a plethora of dedicated applications, online
   and offline wikis, and notetaking software. However, *mdnovel* 
   offers the option of linking images and files with the characters, 
   locations, and items to facilitate access if your external 
   application allows this.
   

.. important::
   If you want to assign **viewpoint characters** to your sections, 
   you first have to `create <characters_menu.html#add>`__ 
   the characters that come into question. 


-----------------


Formatting text
---------------

Section content is expected to be formatted using Markdown.
When exporting Markdown documents, *mdnovel* would not re-format the text,
so you can write in any Markdown dialect you want.
The section editor provides some menu entries and keyboard shortcuts that
insert *Common mark* style markup.

.. important::
   Some character sequences are reserved for the *mdnov* file format, so they
   must not be used in your text. 
   
   Reserved strings:
      - ``@@`` (used as element marker)
      - ``%%`` (used as property marker) 
      - ``---`` (horizontal ruler of any length used as delimiter for YAML-encoded areas) 
   

-----------------


Global find and replace
-----------------------

Currently, the `section editor <editor.html>`__ has no find/replace function.
However, you can close *mdnovel* and open the *.mdnov* project file,
which is actually nothing more than a Markdown file, with any text editor.
This allows you to execute global find/replace operations.
Just be sure not to touch the YAML-encoded areas and the lines containing the reserved strings
shown in the box above.




