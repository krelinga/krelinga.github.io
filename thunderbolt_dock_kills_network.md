---
---

# Thinkpad Thunderbolt 3 Dock Kills The Network

I own a 14" Thinkpad X1 Carbon (5th Generation).  I also have a few big monitors that I wanted to connect to the laptop, and the easiest way to do that was via a Thunderbolt 3 dock.  I ordered the official Thinkpad dock from Amazon (part number 40AN0135US).  When it arrived everything seemed fine, up until I connected the dock to my network via the Ethernet port.  A few days after I did that, my network ground to a halt.  I was able to verify that the problem wasn't upstream, and after restarting all the hardware and having the problem persist I finally got desperate and started just undoing any changes that I recently made to the network.  It was at that point that I unplugged dock, and after that the network started magically working again.  I did some research and found [this thread](https://forums.lenovo.com/t5/Displays-Options-and-Accessories/Thunderbolt-3-dock-40AC-kills-the-network/td-p/4451292) on the Lenovo support forums ... apparently I'm not the first person to discover this issue :-( .  From the discussion there it sounds like it will only happen when there are two monitors plugged into the dock: one via DisplayPort and another via the Thunderbolt 3 downstream port.

For me this isn't a huge issue as the WiFi connection to my network tends to be good enough for nearly everything, but it is probably the most bizarre hardware issue I've ever encountered. 
