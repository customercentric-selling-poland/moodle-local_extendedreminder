# Extended Reminder Plugin for Moodle
By default, Moodle does not send reminders for calendar events. This plugin intends to extend the cases when reminders are sent
out to user.

Currently, notifications are sent for the following:

* When calendar events are created/updated.
* One day or 10 muntes before  calendar event.

The plugin uses Moodle Event API to be listen to these events and uses the Tasks API to send
notifications to users.

## Installation
This plugin can be installed by cloning this repo into the `<moodle-src-root>\local`. Ensure that
the containing folder is named `extendedreminders` and not `moodle_local-extendedreminders`.
