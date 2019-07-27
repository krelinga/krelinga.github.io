# Laptop Font Scaling

My personal projects laptop is a thinkpad X1 Carbon from 2017.  It has a 14" display with a 1080P resolution.  The down-side to this is that all of the fonts are a bit too small by default in XFCE (which is my preferred window manager).  This page tracks various tips and tricks that I've found to scale up the fonts to something more readable.

## Chrome

I discovered two command line flags through [this superuser thread](https://superuser.com/questions/1116767/chrome-ui-size-zoom-levels-in-ubuntu-16-04) which helped me with this:

* `--high-dpi-support=1`, which I assume enables the high dpi support in chrome ... ?
* `--force-device-scale-factor=X`, where you can replace `X` with the scaling factor.  The default scaling factor is `1.0`, I've found that `1.25` works well for me.
