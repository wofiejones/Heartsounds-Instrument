Hello! Here are the necessary steps to start with with your new Heartsounds instrument!

Working with Max Patch:

Download audio samples from Media folder
Download max patch from Source Folder
Use the numbers 1-7 on your computer to trigger the on/off for each sound. 

Working with ZigSim app for Control of Effects:

Download and install ZigSim from the Apple Store or the Google Play Store.
Open the ZigSim patch from the Source folder


Click on the button below the mxj net.local object. This will populate the umenu attached to its right outlet.

In that umenu, choose the en0 option. This will populate the umenu attached to the left outlet of mxj net.local.

In this second umenu, choose the IP address that is formatted as four numbers separated by three dots, e.g., 192.168.0.1
In ZigSim:
Open ZigSim and check 2D TOUCH from the Sensor tab.
Open the Settings tab, and set the following parameters:
Data Destination: Other App
Protocol: UDP
IP Address: Input the IP address you obtained in step 1
Port Number: Choose any number, e.g., 50000
What’s important here is that you set the port attribute of the udpreceive object in Max to this same number.
Message Format: OSC
Message Rate (Per Sec): Any
Device UUID: Any name of your choice. Make sure not to include any spaces in the name.
What’s important is that the route object in Max uses this name after /ZIGSIM/
The provided Max patch is optimized to use ZigSim.
Compass Angle: Any
Beacon: Any
In Max:
Set the port attribute going into the udpreceive object to the same value you provided as Port Number in the ZigSim app.
If you picked a Device UUID in the ZigSim app that isn’t ZigSim, update the values following /ZIGSIM/ in the route object.
Using the various numbers 1-7 on your computer keyboard, you can trigger different healing frequencies from a variety of sounds, and manually control the amount of effects you want applied to the sounds playing. Now just use your creativity and imagination to the different music you can make with these possibilities!

