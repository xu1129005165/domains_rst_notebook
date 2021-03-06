
.. Generated using update-examples, do not edit manually!

.. _examples:

Examples
========

This page showcases Hawkmoth in action.

.. contents::
   :local:
   :depth: 1

.. only:: not have_hawkmoth

   .. note:: The documentation you are viewing was built without Hawkmoth and/or
             its dependencies (perhaps on https://readthedocs.org/). The output
             seen below was pre-generated statically using Hawkmoth, and should
             closely reflect actual results.

Macro
-----

Source
~~~~~~

.. literalinclude:: ../test/example-10-macro.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autodoc:: example-10-macro.c
   

Output
~~~~~~

.. c:autodoc:: example-10-macro.c


Automacro
---------

Source
~~~~~~

.. literalinclude:: ../test/example-10-macro.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:automacro:: DIE
      :file: example-10-macro.c
   

Output
~~~~~~

.. c:namespace-push:: Automacro

.. c:automacro:: DIE
   :file: example-10-macro.c

.. c:namespace-pop::


Variable
--------

Source
~~~~~~

.. literalinclude:: ../test/example-20-variable.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autodoc:: example-20-variable.c
   

Output
~~~~~~

.. c:autodoc:: example-20-variable.c


Autovar
-------

Source
~~~~~~

.. literalinclude:: ../test/example-20-variable.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autovar:: meaning_of_life
      :file: example-20-variable.c
   

Output
~~~~~~

.. c:namespace-push:: Autovar

.. c:autovar:: meaning_of_life
   :file: example-20-variable.c

.. c:namespace-pop::


Typedef
-------

Source
~~~~~~

.. literalinclude:: ../test/example-30-typedef.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autodoc:: example-30-typedef.c
   

Output
~~~~~~

.. c:autodoc:: example-30-typedef.c


Autotype
--------

Source
~~~~~~

.. literalinclude:: ../test/example-30-typedef.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autotype:: list_data_t
      :file: example-30-typedef.c
   

Output
~~~~~~

.. c:namespace-push:: Autotype

.. c:autotype:: list_data_t
   :file: example-30-typedef.c

.. c:namespace-pop::


Enum
----

Source
~~~~~~

.. literalinclude:: ../test/example-40-enum.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autodoc:: example-40-enum.c
   

Output
~~~~~~

.. c:autodoc:: example-40-enum.c


Autoenum
--------

Source
~~~~~~

.. literalinclude:: ../test/example-40-enum.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autoenum:: mode
      :file: example-40-enum.c
      :members: 
   

Output
~~~~~~

.. c:namespace-push:: Autoenum

.. c:autoenum:: mode
   :file: example-40-enum.c
   :members: 

.. c:namespace-pop::


Struct
------

Source
~~~~~~

.. literalinclude:: ../test/example-50-struct.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autodoc:: example-50-struct.c
   

Output
~~~~~~

.. c:autodoc:: example-50-struct.c


Autostruct
----------

Source
~~~~~~

.. literalinclude:: ../test/example-50-struct.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autostruct:: list
      :file: example-50-struct.c
      :members: 
   

Output
~~~~~~

.. c:namespace-push:: Autostruct

.. c:autostruct:: list
   :file: example-50-struct.c
   :members: 

.. c:namespace-pop::


Autounion
---------

Source
~~~~~~

.. literalinclude:: ../test/example-60-autounion.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autounion:: onion
      :file: example-60-autounion.c
      :members: 
   

Output
~~~~~~

.. c:namespace-push:: Autounion

.. c:autounion:: onion
   :file: example-60-autounion.c
   :members: 

.. c:namespace-pop::


Function
--------

Source
~~~~~~

.. literalinclude:: ../test/example-70-function.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autodoc:: example-70-function.c
   

Output
~~~~~~

.. c:autodoc:: example-70-function.c


Preprocessor
------------

Source
~~~~~~

.. literalinclude:: ../test/example-70-preprocessor.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autodoc:: example-70-preprocessor.c
      :clang: -DDEEP_THOUGHT
   

Output
~~~~~~

.. c:autodoc:: example-70-preprocessor.c
   :clang: -DDEEP_THOUGHT


Autofunction
------------

Source
~~~~~~

.. literalinclude:: ../test/example-70-function.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autofunction:: frob
      :file: example-70-function.c
   

Output
~~~~~~

.. c:namespace-push:: Autofunction

.. c:autofunction:: frob
   :file: example-70-function.c

.. c:namespace-pop::


Transform
---------

Source
~~~~~~

.. literalinclude:: ../test/example-75-transform.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autodoc:: example-75-transform.c
      :transform: napoleon
   

Output
~~~~~~

.. c:autodoc:: example-75-transform.c
   :transform: napoleon


Compat
------

Source
~~~~~~

.. literalinclude:: ../test/example-80-compat.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autodoc:: example-80-compat.c
      :transform: javadoc-liberal
   

Output
~~~~~~

.. c:autodoc:: example-80-compat.c
   :transform: javadoc-liberal


Generic
-------

Source
~~~~~~

.. literalinclude:: ../test/example-90-generic.c
   :language: C

Directive
~~~~~~~~~

.. code-block:: rest

   .. c:autodoc:: example-90-generic.c
   

Output
~~~~~~

.. c:autodoc:: example-90-generic.c


