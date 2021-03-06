# Alertify
A Notification Alert for Linux System


## Features ##
* Allows you to set notification alert after given minutes
* Enable or Disable counter to display on your terminal

## Requirements ##
* python2 only

## Installation ##
``sudo python setup.py install``
[Make sure you are using python2]

## Usage ##
### Alert with Timer ###
``alertify time message``

### Alert without Timer
``alertify time message --no-counter``

time - denotes the minutes which can be any integer value

message - the message to display

### Example ###
``alertify 1 Time is up``

Alerts after 1 minute (Timer runs on the terminal)

``alertify 2 Time is up --no-counter``

Alerts after 2 minutes (Timer does not run on the terminal)


## Uninstall ##
To uninstall Alertify, execute the following line in your terminal

``sudo rm -rf /usr/local/bin/alertify``


**NOTE:** Works on Linux and Windows.
