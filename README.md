# Fix for missing option of 60hz refresh rate in Ideapad Gaming 3

![Lenovo Ideapad Gaming 3 Image](/images/laptop_img.png)

## Issue Description: 
Refresh rate fix for lenovo ideapad gaming 3 , it has an issue that 120hz is the only option for refresh rate where user cannot change it to 60hz in order to save battery.

### Step - 1: Check your display specification.
To check display specification, right click on your desktop and click amd software and then go to display -> display specs.

![Display Specs](/images/display-specs.png)

Here you can see FreeSync Range is 48 to 120hz, that means your display supports refresh rate under 120hz , if this doesn't show that means your display have fix refresh rate i.e 120hz.

### Step - 2: Now download a software called [ Custom Resolution Utility](https://www.monitortests.com/download/cru/cru-1.5.2.zip).
Run the software and you will see your current display refresh rate. click on add and enter your display specs and set it to 60hz. Don't forget to add exact values of Disply, Front porch, Sync width, Polarity and Total as shown in amd software.

![CRU](/images/cru-set.png)

Now click ok and restart your Laptop. You will see 60hz option is added to the display settings.

![Display Manager](/images/60hz-option.png)

Click on 60hz and your refresh rate will be set to 60hz. To check 60hz is working you can test it on any online refresh rate checking sites. 

**Note** - If you are getting distortion or lines on your display, then take a hdmi cable and connect the laptop to external monitor and set the refresh rate back to 120hz then check again if their is any detail you missed. however it reversed to 120hz after 10 seconds.

## Method to switch quickly 120hz to 60hz and vice-versa.

Install [ HRC (Hotkey Resolution Changer) ](https://funk.eu/wp-content/plugins/download-monitor/download.php?id=167).
After running the software you will see your resolutions i.e 120hz and 60hz , set your desire shortcut key for both resolutions.
Like - *ctrl + numpad 1 for 120hz and ctrl + numpad 2 for 60hz*.

![HRC](/images/hrc.png)

### Tested on AMD variant of Lenovo IG 3

### My system specs:
- Model: Lenovo Ideapad Gaming 3 (AMD)
- CPU: AMD Ryzen 5600H 
- Graphic: Nvidia gtx 1650
- Ram: 16 GB
- OS: Windows 11

Same can be done for Intel variant but you have to check display specs from other tools or software.
**I hope it worked for you.**
