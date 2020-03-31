# kpad

Kake Pad Gambas version

This program is a translation from the perl version of kake pad originally located at https://sourceforge.net/projects/kpad/ also written by me.
Based on some very old perl code, version 5.2.1. This is not a one for one copy as this conversion both has improvements and 
lacks one or two features from my original at this moment. I've also decieded to this version should be under a different license, the MIT license. This is what will be actively developed going forward. 

# This program requires: 

Gambas 3.14.3, Linux

Note Gambas doesn't have a windows port, but might run under cygwin. Therefore running this app under Windows might be tricky.

# And these Gambas componets

gb
gb.eval
gb.eval.highlight
gb.form
gb.form.dialog
gb.form.editor
gb.form.terminal
gb.gui.qt
gb.image *
gb.pcre
gb.settings *
gb.signal *
gb.term
gb.util


# Written on Manjaro Linux with the latest available AUR repo Gambas

* Note may not yet be used and some function as dependencies by others. 

# Why Gambas? 

I truely love Perl, but I wanted to revisit Gambas. Mainly, for the challenge of doing the conversion to see how easy it was and how hard it would be. Gambas is a Basic dialect and I've always had a soft spot for Basic. I also wanted to have the chance to fully test Gambas, its IDE and it's capabilities and this has allowed me to do this.

# Progress so far

Progress has been great and most of this was written inside two days from scratch. I had a few hiccups here and there to work around as Gambas while not a bad langauge either lacked some documentation or features. With a little research and presistence I've been able to work through all of it. 

# TODO

Implement the plugin system, mainly. Also a good find and replace function. Also expand on the capabilities of the componets involved. 
