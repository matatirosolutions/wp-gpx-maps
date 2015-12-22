# WP GPX plugin 

This is a fork of https://github.com/devfarm-it/wp-gpx-maps to allow for modifications to suit personal style.

Changes made in this version
 - added maxSpeed
 - modified the calulation of average speed to max($_dist) / (max($_time) - min($_time))
 - modified the display of the status table to display data in a table
 - fixed issues with labels in the admin console not matching their purpose
 - fixed an issue with the control of the display of speed pulling from an incorrect variable