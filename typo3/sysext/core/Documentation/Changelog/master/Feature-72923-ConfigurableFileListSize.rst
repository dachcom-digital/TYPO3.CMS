==================================================================================
Feature: #72923 - Configure the number of files shown per page in file list module
==================================================================================

Description
===========

It is now possible to configure the maximum number of files shown per page in the file list module using User TSconfig.

.. code-block:: typoscript

   mod.file_list {
      filesPerPage = 40
   }

