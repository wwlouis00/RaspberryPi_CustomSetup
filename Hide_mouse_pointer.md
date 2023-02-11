# How to permanently hide mouse pointer or cursor on Raspberry PI?
I simply added a nocursor option as follows in the file (/etc/lightdm/lightdm.conf)
- xserver-command = X -nocursor
