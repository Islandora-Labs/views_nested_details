# Views Nested Details

This Drupal module provides a Views formatter (called "Nested Details") that displays content in a nested collapsed accordion format. It was designed for listing issues of a newspaper or other contexts where many items need to be displayed in a "drill down" fashion.

To use this to display content such as newspaper issues, create a View with a block display, and use contextual filters to filter your content to issues of a particular newspaper. In that View, include the issued date field (which may be hidden from display) which will be used as the Grouping field in the settings of the Nested Details format. You may do this multiple times, e.g. first with the issue date formatted as year-only, then for the issue date formatted as month-only. 

After this, place the block to appear on the newspapers' landing pages using the block placement method of your choice. This is placed via Context in the starter site.


Additional Info: https://docs.lefaive.ca/wiki/Views_Nested_Details_(Drupal_module)
