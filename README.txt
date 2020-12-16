.. caution:: 

    This repository has been archived. If you want to work on it please open a ticket in https://github.com/zopefoundation/meta/issues requesting its unarchival.


=====================================================
Demo Applications for ``z3c.form`` and ``z3c.formui``
=====================================================

This package contains several small demo applications for the ``z3c.form`` and
``z3c.formui`` packages.

* TABLE- versus DIV-based layout of all widgets.

* A simple Hello World message application demonstrating the easiest way to
  write add, edit and display forms.

* A simple calculator showing the flexibility of the new action declaration
  framework by declaring different classes of buttons.

* A linear wizard shows off the sub-form capabilities of z3c.form. It also
  demonstrates how one can overcome the short-coming of an object widget.

* A simple table/spreadsheet that allows adding and editing as simple content
  object. This demo also shows the usage of forms and ``zc.table`` at the same
  time.

Running the Demo out of the box
-------------------------------

You can also run the demo directly without manually installing Zope 3::

  $ git clone https://github.com/zopefoundation/z3c.formdemo
  $ cd z3c.formdemo
  $ python bootstrap.py
  $ ./bin/buildout
  $ ./bin/demo fg

Then access the demo site using:

  http://localhost:8080/
