.. This is a reStructuredText document.
.. See http://docutils.sourceforge.net/rst.html for syntax help.
..
.. Section conventions:
..     =====
..     Title
..     =====
..
..     Heading 1
..     =========
..
..     Heading 2
..     ---------
..
..     Heading 3
..     `````````
..
..     Heading 4
..     '''''''''
..
..     Heading 5
..     .........
..

=====
Title
=====

.. note::

    This is a note that contains more structure.

    #. Bullet 1

       a. sub-bullet 1

       #. sub-bullet 2

    End of note admonition.



.. contents:: Table of Contents
   :depth: 5

H1.0
====

#. Test internal link where target is created elsewhere in
   this document: `internal link 1`_

#. Test internal link where target is created just before
   a section heading: `internal link 2`_ (I think this doesn't
   work because you get section targets automatically based
   on section name.)

#. Test internal link to section heading text as the target
   (without having explicitly created a target there):
   `H4`_

#. Test *external* link: `AWS Service Health Dashboard`_

#. Test external link with fold-in form `reStructuredText
   <http://docutils.sourceforge.net/rst.html>`_
   work?


H1.1
====

Some text and an ``inline literal``.

.. code::

    Some code.

.. _`internal link 1`:

The internal link "internal link 1" should take you here.

* a
* b
* c

#. a
#. b
#. c


.. _`internal link 2`:

H1.2
====

The link "internal link 2" should take you here.

Here is a table.

+------------------------------------------+---------------+---------+
| Column1                                  | Column2       | Column3 |
+==========================================+===============+=========+
| r1.c1                                    | r1.c2         | r1.c3   |
+------------------------------------------+---------------+---------+
| r2.c1                                    | r2.c2         | r2.c3   |
+------------------------------------------+---------------+---------+



H2
--


H3
``

Some text in the H3 section.


H4
''

Try to link to another file in the same folder as this
file: `other.rst
<other.rst>`_

Try to link to `method1`_, which is in ``methods/method1.rst``.

Try to include an image:

.. image:: test.jpg



.. Internal links:

.. _`method1`: methods/method1.rst


.. External links:

.. _`AWS Service Health Dashboard`: https://status.aws.amazon.com/


