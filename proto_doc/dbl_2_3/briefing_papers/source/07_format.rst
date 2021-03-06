#################
FORMAT - OVERVIEW
#################

The format section is highly medium-dependent. The details for each of the
five existing media are provided in subsequent chapters.

************************
PROPOSED CHANGES FOR 2.3
************************

===========
Conventions
===========

Conventions are intended to provide a mechanism for subtyping media, allowing
greater flexibility along with improved server-side checking and bundle-consumer
visibility.

.. code-block:: xml

    <convention type="structure" version="1.0">usx_dirs</convention>

Zero or more convention elements would be allowed for each entry. In the absence
of a convention, the entry may or not comply, ie *caveat emptor*.

**@type** is one of

* **structure** ie the "directory" structure, eg "usx-dirs"

* **content-format** ie the standard to which specific resources comply, eg "usx3"

* **content** ie the actual content of resources, eg, "usx-refs"

**@version** is required since more complex conventions are likely to evolve.

The enum of conventions will need to be defined in consultation with stakeholders. x-.* should be
supported for emerging conventions.

****************************************
ISSUES TO CONSIDER FOR SCRIPTURE BURRITO
****************************************

None.
