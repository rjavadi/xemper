# xemper
An script for properly seeing memory usage percentage using Xfce4 Generic Monitor in xfce panel.

## Why?
I had a desktop with 4 gigabytes of RAM.
##### From time to time it went almost dead and unusable due to RAM deficiency or swapping.
I decided to do something quickly and smartly.Created a small script to show used memory on the panel. I've created a variable, "threshold_percentage", in the script which is set to 65 percent by default. 
##### If memory usage goes above 65 percent, I'll be notified. Additionally, I can see the memory usage percentage all the time in the panel and I can take action before it's too late to close extra apps or browser tabs :)

## Installation

This script is intended to be used in xfce desktop environment. For example if you are using Xubuntu you can enjoy it.

#### Install Generic Monitor for xfce4:

    sudo apt-get install xfce4-genmon-plugin

#### Then:

    cd ~
    git clone https://github.com/eranik/xemper

#### Now do as follow step-by-step:

1. Right-click on xfce panel and press add new item:

![xfce-panel-add-new-item](./images-for-readme/1-xfce-panel-add-new-item.jpg)

2. Search for Generic Monitor:
![new-generic-monitor-right-click](./images-for-readme/3-new-generic-monitor-right-click.jpg)

3. Right click on the Generic Monitor Plugin item added to your xfce panel and click properties:

![xfce-panel-add-generic-monitor](./images-for-readme/2-xfce-panel-add-generic-monitor.jpg)

4. In the properties provide the path to "memory_threshold_notification" script of this repository, also set the font size to 32 for readability: 

![generic-monitor-settings](./images-for-readme/4-generic-monitor-settings.jpg)
