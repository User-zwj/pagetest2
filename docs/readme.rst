This is the README file.
========================


.. _Ref1:

This is the content when we refer Ref1.
This is the content when we refer Ref1.
This is the content when we refer Ref1.
This is the content when we refer Ref1.
This is the content when we refer Ref1.
This is the content when we refer Ref1.
This is the content when we refer Ref1.
This is the content when we refer Ref1.
This is the content when we refer Ref1.
This is the content when we refer Ref1.
This is the content when we refer Ref1.
This is the content when we refer Ref1.
This is the content when we refer Ref1.
This is the content when we refer Ref1.
This is the content when we refer Ref1.
This is the content when we refer Ref1.
This is the content when we refer Ref1.
This is the content when we refer Ref1.
This is the content when we refer Ref1.
This is the content when we refer Ref1.
This is the content when we refer Ref1.


.. seealso:: This is a simple **seealso** note.


*****************
This is the Title
*****************

**This is a bulleted list: (extra space before the bulleted list)**

* Bullet 1
* Bullet 2
* Bullet 3


**This is a numbered list:**

#. Number 1
#. Number 2
#. Number 3


Subtitle
###########

.. warning:: This is a warning message.

Refer to Ref1_

Subsubtitle
***********

.. note:: This is a note.

*********************
Sphinx and RST syntax
*********************

The guide can be accessed from `Link of Guide <https://thomas-cokelaer.info/tutorials/sphinx/rest_syntax.html>`_

Link to Subtitle(#) `Subtitle`_

This is a html code block:

.. code-block:: html
    :linenos:

    <h1>code block example</h1>


This is a python code block::

    import numpy as np
    import matplotlib.pyplot as plt

Load python code from an existing file:

.. literalinclude:: _static/sample.py
    :linenos:
    :language: python


This is the table:

+---------+---------+-----------+
| 1       |  2      |  3        |
+---------+---------+-----------+

Multicells tables (Method 1):

+------------+------------+-----------+
| Header 1   | Header 2   | Header 3  |
+============+============+===========+
| body row 1 | column 2   | column 3  |
+------------+------------+-----------+
| body row 2 | Cells may span columns.|
+------------+------------+-----------+
| body row 3 | Cells may  | - Cells   |
+------------+ span rows. | - contain |
| body row 4 |            | - blocks. |
+------------+------------+-----------+

Multicells tables (Method 2):

=====  =====  ======
   Inputs     Output
------------  ------
  A      B    A or B
=====  =====  ======
False  False  False
True   False  True
=====  =====  ======

.. currentmodule:: square 

This is the content from .... paper as shown in the citation.
[CIT2002]_



.. topic:: Your Topic Title

    Subsequent indented lines comprise
    the body of the topic, and are
    interpreted as body elements.

This is a paragraph. This is a paragraph.

.. sidebar:: Sidebar Title
    :subtitle: Optional Sidebar Subtitle

    Subsequent indented lines comprise
    the body of the sidebar, and are
    interpreted as body elements.

.. comments (not working)

This is a comment.


.. [CIT2002] A citation
          (as often used in journals).



Some text that requires a footnote [#f1]_ .

This is a paragraph. This is a paragraph.
This is a paragraph. This is a paragraph.
This is a paragraph. This is a paragraph.
This is a paragraph. This is a paragraph.
This is a paragraph. This is a paragraph.
This is a paragraph. This is a paragraph.
This is a paragraph. This is a paragraph.


.. rubric:: Footnotes

.. [#f1] Text of the first footnote.
