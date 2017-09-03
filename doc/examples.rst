
.. Generated using update-examples, do not edit manually!

.. _examples:

Examples
========

This page showcases Hawkmoth in action.

.. contents::
   :local:
   :depth: 1

.. only:: not have_hawkmoth

   .. note:: The documentation was built without Hawkmoth and/or its
             dependencies (perhaps on https://readthedocs.org/). The output seen
             below was not dynamically generated.

Macro
-----

Source
~~~~~~

.. literalinclude:: examples/example-10-macro.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autodoc:: examples/example-10-macro.c
      

Output
~~~~~~

.. c:autodoc:: examples/example-10-macro.c
   

.. only:: not have_hawkmoth

   .. include:: examples/example-10-macro.stdout

Variable
--------

Source
~~~~~~

.. literalinclude:: examples/example-20-variable.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autodoc:: examples/example-20-variable.c
      

Output
~~~~~~

.. c:autodoc:: examples/example-20-variable.c
   

.. only:: not have_hawkmoth

   .. include:: examples/example-20-variable.stdout

Typedef
-------

Source
~~~~~~

.. literalinclude:: examples/example-30-typedef.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autodoc:: examples/example-30-typedef.c
      

Output
~~~~~~

.. c:autodoc:: examples/example-30-typedef.c
   

.. only:: not have_hawkmoth

   .. include:: examples/example-30-typedef.stdout

Enum
----

Source
~~~~~~

.. literalinclude:: examples/example-40-enum.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autodoc:: examples/example-40-enum.c
      

Output
~~~~~~

.. c:autodoc:: examples/example-40-enum.c
   

.. only:: not have_hawkmoth

   .. include:: examples/example-40-enum.stdout

Struct
------

Source
~~~~~~

.. literalinclude:: examples/example-50-struct.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autodoc:: examples/example-50-struct.c
      

Output
~~~~~~

.. c:autodoc:: examples/example-50-struct.c
   

.. only:: not have_hawkmoth

   .. include:: examples/example-50-struct.stdout

Function
--------

Source
~~~~~~

.. literalinclude:: examples/example-70-function.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autodoc:: examples/example-70-function.c
      

Output
~~~~~~

.. c:autodoc:: examples/example-70-function.c
   

.. only:: not have_hawkmoth

   .. include:: examples/example-70-function.stdout

Compat
------

Source
~~~~~~

.. literalinclude:: examples/example-80-compat.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autodoc:: examples/example-80-compat.c
      :compat: javadoc-liberal

Output
~~~~~~

.. c:autodoc:: examples/example-80-compat.c
   :compat: javadoc-liberal

.. only:: not have_hawkmoth

   .. include:: examples/example-80-compat.stdout

Generic
-------

Source
~~~~~~

.. literalinclude:: examples/example-90-generic.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autodoc:: examples/example-90-generic.c
      

Output
~~~~~~

.. c:autodoc:: examples/example-90-generic.c
   

.. only:: not have_hawkmoth

   .. include:: examples/example-90-generic.stdout
