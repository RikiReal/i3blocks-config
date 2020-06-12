This is my simple configuration for the i3-blocks status bar

You can find all the scripts in the 'scripts' directory
Some of the scripts that I used are standard scripts that I copied and modified from here: https://github.com/vivien/i3blocks-contrib.
I do not own the copyright to these scripts. Please refer to the original authors. 
The config file contains symbols that are only available with font-awesome.

<h3>SCRIPTS</h3>

This is the directory where all the scripts are stored.

<h4>Datetime</h4>
Get the current datetime and display it. If the user clicks on it a calendar opens. Courtesy of 'YAD'.

<h4>Diskusage</h4>
Get the available disk space on the root and home partitions.
Additionaly, display text in green if root disk usage is 20%, orange if it is 50%, and red if it is 80%.

<h4>Ethernet</h4>
Display the status of the 'ethernet0' interface. 
Displays the word 'down' in red if the interface is down.

<h4>Memoryusage</h4>
Display the used and available memory. Visually seperates the two with a '/'.
If 50% of memory is used, print the text in green, 60%->orange, 80%->red.

<h4>Settings</h4>
If the user clicks on the icon, the KDE systemsettings are opened. That's it.

<h4>Weather</h4>
Get the current weather for your current location (handy if you don't want to look outside).
Doesn't work always, sometimes nothing is displayed. Reload i3 it that happens. But it is not really that big of a deal.

<h4>Wifi</h4>
Display the status of the 'wlan0' interface.
If wifi is down the word 'down' is displayed in red letters.
Also, if the quality of your wifi is >80% -> green, 60% -> orange, 40% -> red.


