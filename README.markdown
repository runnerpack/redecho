RedEcho
=======

_Helping the Virtual Boy development community for under 0.0000000001 years!_

I'm still trying to decide on the right language, GUI toolkit, etc. to use and whether to call the existing VBSG executable, or to absorb the original code and make it stand-alone.

Right now I'm leaning toward Ruby + Gosu + GGLib and passing generated text files to VBSG. Some other options include (in rough order from more to less likely):

<dl>
<dt>C# (.NET/mono)</dt>
<dt>Adobe AIR</dt>
<dt>C/C++ and:</dt>
<dd><dl>
<dt>plain Win32 API</dt>
<dt>SDL w/ some kind of SDL GUI lib</dt>
<dt>SDL w/ scratch-built interface stuff</dt>
<dt>wxWindows (not likely)</dt>
</dl></dd>
<dt>Java</dt>
</dl>

I'm probably going with a "tabbed" interface. Outside the tabbed area will be a list of commands and the controls for manipulating the list (add, remove, clone, reorder, etc.). Things like context menus and drag/drop will depend on the environment/toolkit used.

Command List
------------

Possible productivity enhancements for the list of commands include:

* Groups for organization
* Automatic, intelligent grouping by VSU channel
* Saving standard sequences in a "library"
* SFXr-like generation of pleasing sound-fx
