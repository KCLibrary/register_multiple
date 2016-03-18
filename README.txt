#Register Multiple Drupal Module for use with Entity Registration Module#

Reigster multiple allows for the registering of all the future
enabled events of a given registration type.

#Installation#
Enable the module and clear the cache to display pages.
If you have a date field you will need to update your machine name field. "field_date_calendar"
$date = $node->field_date_calendar['und'][0]['value'];

You can find the url to the multiple registration page at /register/LABEL-OF-YOUR-REGISTRATION-TYPE