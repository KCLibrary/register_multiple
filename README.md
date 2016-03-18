# Register Multiple Drupal Module for use with Entity Registration Module #

Reigster multiple allows for the registering of all the future
enabled events of a given registration type.

# Installation #
Enable the module and clear the cache to display pages.

If you have a date field you will need to update your machine name field.
``` field_date_calendar ```
``` $date = $node->field_date_calendar['und'][0]['value']; ```

Or remove the date conditional and just use ``` $checkbox_values[$node->nid] = $node->title; ``` to display the title.

You can find the url of the multiple registration page(s) at /register/LABEL-OF-YOUR-REGISTRATION-TYPE