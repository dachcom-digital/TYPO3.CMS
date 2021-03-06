=======================================================================
Breaking: #75237 - Removal of div ce-bodytext might cause layout issues
=======================================================================

Description
===========

If neither bodytext nor header were entered in the TextMedia element, the div element containing the class ce-bodytext will be suppressed.


Impact
======

The missing div could cause layout problems, if the layout and CSS depends on it.


Affected Installations
======================

All installations relying on <div class="ce-bodytext">


Migration
=========

Either change the CSS or use a custom template without all the conditions.

.. index:: fluid, ext:fluid_styled_content
