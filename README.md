# IP-by-SMS

Simple Ruby Script to get the LAN IP of the network on which my Raspberry Pi is connected via SMS

Main objective behind this script was to get the LAN IP of my Raspberry Pi when it is being used in an headless mode.

Ideally people reserve an IP on the router against the MAC ID of the Raspberry Pi, however, sometimes you can't change settings in the router. This program intends to solve this issue.

It's a simple Ruby application which uses MSG91's API's to trigger SMS to the predefined set of number(s).

The thought process behind this is to trigger a script on the event of establishing internet connection through the saved WiFi Passwords.

