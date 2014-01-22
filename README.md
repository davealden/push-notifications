
# push-notifications icinga/nagios notifications #

This program is used by icinga/nagios to notify an administrator of any
issues via push notifications.  It has been tested against Prowl and
Pushover.  We've written code to work with Notify My Android, but haven't
been able to test it (due to a lack of an Android device) -- please let
us know if you try it.

More info on the various push notification services is available from:

  nma - http://www.notifymyandroid.com/ - android only
  prowl - http://www.prowlapp.com/ - iOS only
  pushover - https://pushover.net - both android and iOS

I've included example_commands.cfg and example_contacts.cfg as examples
of how to use this script.
