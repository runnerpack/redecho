RedEcho
=======

_Helping the Virtual Boy development community for under 0.0000000001 years!_

Project Status
--------------

On hold...

I'm still trying to decide on the right language, GUI toolkit, etc. to use and whether to call the existing VBSG executable, or to absorb the original code and make it stand-alone.

Right now I'm leaning toward Ruby + Gosu + GGLib -- passing generated text files to VBSG and playing the resulting WAV. Some other options include (in rough order from more to less likely):

* C# (.NET/mono)
* Adobe AIR
* C/C++ and:
<dl>
<dd>plain Win32 API</dd>
<dd>SDL w/ some kind of SDL GUI lib</dd>
<dd>SDL w/ scratch-built interface stuff</dd>
</dl>
* Java

I'll probably go with a "tabbed" interface. Outside the tabbed area will be a list of commands and the controls for manipulating the list (add, remove, clone, reorder, etc.). Things like context menus and drag/drop will depend on the environment/toolkit used.

Beyond the planning required, setting aside time to actually work on it is (unsurprisingly) difficult.

Command List
------------

Possible productivity enhancements for the list of commands include:

* Colors/icons
* Grouping commands for organization
* Automatic, intelligent grouping by VSU channel
* Saving standard sequences in a "library"
* SFXr-like random generation of standard sound-fx (or maybe just import support for SFXr files)
