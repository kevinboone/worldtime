# worldtime

A simple Linux script to display times around the world, at some
specified time in some specified location.

For example:

    worldtime 1:23 paris

Display times around the world when it's 1:23 (AM) in Paris, France.
If there are multiple cities that match "paris" (unlikely, with the
usual Linux timezone database) you could be more particular:

    worldtime 1:23 Europe/Paris 

Note that the region name _can't_ be a timezone, like "IST". The script
make no provision for this kind of operation, because these timezone
names are ambiguous.

The time can be AM/PM, e.g., "2 pm"; but note that the whole time 
will need to be enclosed in quotes if you include a space:

    worldtime "2 pm" calcutta 

With no arguments, the script displays times around the world now.

For more information, see https://kevinboone.me/clh_worldtime.html.

