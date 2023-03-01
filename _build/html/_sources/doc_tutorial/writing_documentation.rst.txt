Step 1: Writing Documentation
==============================
In order to add documentation to the website, you first need to *write* said 
documentation. This section will teach you the basics of ReStructuredText and 
how to write documentation in it. 

Making the File
----------------
A ReStructuredText file is a file with the extension `.rst`. Make a file and name
it after whatever you are going to be documenting, and end it with the `.rst` file
extension.

ReStructuredText is a powerful format because it allows you to do much more than just
plain text. You can make notes, warnings, content tables, images, links, and so much
more.

Intro to ReStructuredText
--------------------------
ReStructured text has special tags that you can use to bring up special things. 
For example:

.. note::
    This is a note!

.. warning:: 
    This is a warning!

.. error:: 
    This is an error!

.. list-table:: Table
    :header-rows: 0

    * - This is a list table!
      - This can store content!
    * - And even more!
      - Wow!
    * - It's amazing!
      - Super cool!

For a full, in-depth guide on ReStructuredText, go to `this helpful site`_
to learn more.

.. _this helpful site: https://sphinx-tutorial.readthedocs.io/step-1/

Organizing Documentation
-------------------------
Documentation varies based on the component or process that you are documenting. 
Here are some helpful tips that will apply in any circumstance:

- Organize it properly. Make sure it is like other similar documentation.
- Keep it short and simple. More information makes it hard to find what you want.
- Include lots of technical information. This could be useful if you need something
  specific later on.

Next Steps
----------
Read on to find out how to get your documentation including in the CougarDocs
website!