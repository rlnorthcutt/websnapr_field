websnapr_field
==============
Original D6 module: https://drupal.org/project/websnapr_field

Initial D7 port: https://drupal.org/node/1083118 by henkiejan

/* $Id: $ */

-- SUMMARY --

Websnapr Field provides a simple means to display web page thumbnails using
the Websnapr service.

For a full description of the module, visit the project page:
  http://drupal.org/project/websnapr_field

To submit bug reports and feature suggestions, or to track changes:
  http://drupal.org/project/issues/websnapr_field


-- REQUIREMENTS --

None.


-- INSTALLATION --

* Install as usual, see http://drupal.org/node/70151 for further information.


-- CONFIGURATION --

* A prerequisite for the use of this module is a Websnapr account. One
  account is required for each site on which it is used. Register at
  Websnapr.com and get your account key before continuing.
* Login as a site adminstrator and go to Administer >> Site configuration >>
  Websnapr account. Enter your Websnapr account key into the field and save it.
* From Content Management >> Content types you can now add fields you want to
  display as thumbnails using the Link data type.
* For each field, on the Display Fields panel select one of the Websnapr options
  to display the field as a thumbnail image.

-- CUSTOMIZATION --

* To change the way a Websnapr field is displayed you may override the theme function:

     Copy the entire theme_websnapr_field_formatter() function into your template.php,
     rename it to phptemplate_websnapr_field_formatter() or THEMENAME_websnapr_field_formatter(),
     and customize the output according to your needs.


-- CONTACT --

Current maintainers:
* Alfred Armstrong (alfaguru) - http://drupal.org/user/112814
