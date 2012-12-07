Mate Session Management - Kupfer Plugin
=======================================

Mate Session Management plugin for Kupfer, that allows you to lock
the screen, log off and call the shut down panel.

Recently I upgraded my Linux Mint to 2012.10 and it came with MATE, a fork to the unmaintained Gnome 2.
Kupfer is an app launcher, one of the first things I install on my fresh linuxes. 
But this time the session management (like Shut Down and Lock Screen) commands didn't work.

The problem is that the default APT package for Kupfer only have plugins for GNOME and XFCE session management, 
and lacked support to MATE. Until now.

Based on plugin for Gnome, written by Ulrik Sverdrup.

Installation Instructions
-------------------------

- Download session_mate.py
- Copy or Move that file to ~/.local/share/kupfer/plugins/
- Restart Kupfer
- Open Kupfer Preferences
- Disable GNOME and XFCE Session Managemente plugins
- Enable MATE Session Management plugin
- Call Kupfer to Lock your Screen, Logoff or Shut Down
- Be happy
