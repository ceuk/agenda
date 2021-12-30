# Nice Khal Agenda

![image](https://user-images.githubusercontent.com/1681236/147759942-0b613bf3-f333-448c-b748-f1a40de79332.png)


An nice-looking agenda view optimized for MS teams events

Requires NodeJS and [Khal](https://github.com/pimutils/khal).

## Setup

* Clone this repo Run `npm i` or `yarn` Create a symlink to somewhere in your
PATH: `sudo ln -s ~/PATH/TO/THIS/REPO/agenda /usr/local/bin/agenda`
* (optional) set the `AGENDA_CALENDARS` env var (`export
AGENDA_CALENDARS="'mycalendarnamefromkhal'"`) to filter by specific calendar
name(s)
* Type `agenda` to start. 


*Note: this script expects the Khal database to be at the default location of
`$XDG_DATA_HOME/khal/khal.db`. If it's in a different place you'll need to edit
line 8 of the `agenda` file.*


## Features & Usage

* Highlight an item with j/k to go up/down.
* Press enter to open the link to the online meeting if one was found in the
current event
* The agenda view will auto-refresh itself
