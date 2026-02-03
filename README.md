# ArchWorkStation
A functional WorkStation (Based on MeinArchInstaller, another project of mine). This is intended to be semi-automatic and configurated Environment. X11 and Wayland is used depending the kind of Environment wanted
Arch Linux is flexible, but use SystemD. I don't want to fight with it, but I'll use anyway for more "easy and friendly" with most of the apps available.
Minimal vs Pragmatism is the dilemma I fought for. So, if this document is so extensive, I'll separate Documentation with Readme (I guess I'll do it some of this days hahaha)

## Why?
I found an issue I want to face for. Modern usage is so heavy for modest Hardware. DE's and WM's are a kind of bloated, but still usable.
My dilemma start here. Install some DE?, or maybe a WM? Saving resources really matters?
So, I'll gonna answer this while I start planning and commiting changes, in a near future. 

With that in mind, let's go for a summary
## Summary
As you may think, is time consuming, but worthy if everything is OK.
Some goals for this project are:
- Minimal
- Functional
- Long Term Usable
- Practical
- No Distractions
- Offline First
So, in order to reach this goals, this project will be divided in two: Minimal and Practical

---
## Minimal Installation
As the name say, consist in the most minimal for being usable, even with just terminal and not GUI (Just terminal). If someone want a MINIMAL installation but with GUI, I adopted a "old vibe" package selection, using the the most lower RAM as possible (that's why I chose FVWM or NsCDE [FVWM based, but with CDE look]). Each resource matter, so, we need to save the most we can.

---
## Practical Installation
So, doesn't matter what to use, but need a reliable, usable, daily-driver system. Supposing you have good Hardware, system may use 1.5 GiB aprox.
KDE Plasma, GNOME, Hyprland, and others DE's and WM's are allowed for this purpose.

---
## And MAIN.SH?
The file 'main.sh' is supposed to be the "logic" of project. Both kinds of installations starts here. Same base, with important apps that both use. Automatic installation and "rice" (looks for the environment) are intended to include.

For avoid bloat, scripts with .sh extensions will be the principal way to reach all of this.
Thanks :D
