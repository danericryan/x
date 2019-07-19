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

    #. b1

       a. b1.b1

       #. b1.b2

    #. Does this internal link `internal link1`_
       work?

    #. Does this internal link to a heading `link to h3`_
       work?

    #. Does this external link `reStructuredText
       <http://docutils.sourceforge.net/rst.html>`_
       work?

    #. Does this indirect external link `AWS Service Health Dashboard`_
       work?

       a. b3.b1

          .. code::

              Some code.



.. contents:: Table of Contents
   :depth: 5


H1.1
====

Some text and an ``inline literal``.

.. _`internal link1`:

The internal link "internal link1" should take you here.

* a
* b
* c

#. a
#. b
#. c

H1.2
====

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

The internal link "link to h3" should take you here.

.. _`link to h3`:

Some text in the H3 section.


H4
''

Try to link to `other.rst
<other.rst>`_

Try to link to `method1`_, which is in ``methods/method1.rst``.

Try to include an image:

.. image:: test.jpg



.. Internal links:

.. _`method1`: methods/method1.rst


.. External links:

.. _`AWS Service Health Dashboard`: https://status.aws.amazon.com/


