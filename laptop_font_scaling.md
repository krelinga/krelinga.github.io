# Laptop Font Scaling

* TOC
{:toc}

My personal projects laptop is a thinkpad X1 Carbon from 2017.  It has a 14" display with a 1080P resolution.  The down-side to this is that all of the fonts are a bit too small by default in XFCE (which is my preferred window manager).  This page tracks various tips and tricks that I've found to scale up the fonts to something more readable.

## Chrome

I discovered two command line flags through [this superuser thread](https://superuser.com/questions/1116767/chrome-ui-size-zoom-levels-in-ubuntu-16-04) which helped me with this:

* `--high-dpi-support=1`, which I assume enables the high dpi support in chrome ... ?
* `--force-device-scale-factor=X`, where you can replace `X` with the scaling factor.  The default scaling factor is `1.0`, I've found that `1.25` works well for me.

## Intellij IDEA

I'm trying to get more used to IDEs in general, and decided to start with IntelliJ IDEA.  Getting used to the IDE is made substantially easier when I can actaully read the text ;-) .  There are a number of different font settings to tweak here:

* `Settings > Editor > Font`
* `Settings > Editor > Color Scheme > Console Font`
* `Settings > Appearance & Behavior > Appearance > Use Custom Font (Size)`

Note that some of these may be changed by default when you change the others.  I've found that 16 point font is about right for me.

## XFCE Theme

XFCE provides an alternative theme to help make the border directions around various windows a bit larger.  There are two such themes right now:

* `Default-hidpi`: a smaller increase in size.
* `Default-xhidpi`: a larger increase in size.

These themes can be selected in the `Window Manager` settings application.
