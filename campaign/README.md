CONTENTS OF THIS FILE
---------------------

 * Introduction
 * Requirements
 * Installation
 * Configuration
 * Functionality
 * Troubleshooting
 * Extend
 * Maintainers

INTRODUCTION
------------

This module help us to create basic layout of campaign page.


REQUIREMENTS
------------

This module requires the following modules:

* Paragraphs (https://www.drupal.org/project/paragraphs)
* Entity Reference Revisions(https://www.drupal.org/project/entity_reference_revisions)

INSTALLATION
------------

* Install as you would normally install a contributed Drupal module. Visit
   https://www.drupal.org/node/1897420 for further information.


CONFIGURATION
-------------

* No configuration required.


FUNCTIONALITY
-------------

* A title, Template type can be added. 

* Any type of component can be added .

* Tint component can be added .

* CSS changes based on the template type chosen.

* Webforms can be added .

TROUBLESHOOTING
---------------

* If the content type does not display, check the following:

  - Check whether the module is installed properly.

EXTEND
------

* hook_preprocess_html for adding class in the body based on the template chosen.

* hook_form_node_alter and submit alter to get the value chosen in component set dropdown.



MAINTAINERS
-----------

* Dev team.