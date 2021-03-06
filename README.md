<h1>About Date Basic for Backdrop</h1>
-------------------------

Backdrop v1.2 has included the functionality of this module in core and does not require this contributed module.

This module provides flexible date/time field types in Backdrop and a Date API that other modules can use. 

In its current version, forked from Drupal's Date module, it provides for three types of date field: a Unix timestamp stored as an integer; an ISO format date stored as a text field; and a basic date stored as a MySQL datetime field.

Additionally it provides three different ways for a user to input a date: a text field using one of many PHP date-time formats; a drop-down select list for day, month and year; and a javascript pop-up calendar for day, month and year.

The module includes the possibility of a date-time pair, defining the start and finish times for an event.

An included Date Views module provides integration with Views.

Remaining functions not in Date Basic nor in core v1.2 are being made available in contributed modules date_all_day, date_tools and date_repeat. Please see these modules for more details



<h2>Status</h2>

This port to Backdrop now passes most of its inbuilt tests but there are still some residual problems.


<h2>Help & Documentation</h2>

Information for developers is available in readme.txt



<h2>License</h2>

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.
    
    
<h2>Current Maintainers</h2>

<h3>For Drupal:</h3>

vijaycs85 - Vijayachandran Mani;  cafuego - Peter Lieverdink;  KarenS - Karen Stevenson;  arlinsandbulte - Arlin Sandbulte;  developer-x


<h3>Port to Backdrop:</h3>
Graham Oliver github.com/Graham-72

<h3>Acknowledgement</h3>

This port to Backdrop would not, of course, be possible without all the work done by the developers and maintainers of the Drupal module.
