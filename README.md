# Nice Khal Agenda

![image](https://user-images.githubusercontent.com/1681236/147759942-0b613bf3-f333-448c-b748-f1a40de79332.png)


An nice-looking agenda view optimized for MS teams events

Requires [Khal](https://github.com/pimutils/khal).

## Setup

* Clone this repo
* Run `npm i` or `yarn`
* Either set the `AGENDA_CALENDARS` env var (`export AGENDA_CALENDARS="'mycalendarnamefromkhal'"`) or hardcode the variable near the top of `./agenda`
* Create a symlink to somewhere in your PATH: `sudo ln -s ~/path/to/this/repo/agenda /usr/local/bin/agenda`
* Type `agenda` to start. 


## Features & Usage

* Highlight an item with j/k to go up/down. 
* Press enter to open the link to the online meeting if one was found in the current event
* The agenda view will auto-refresh itself
