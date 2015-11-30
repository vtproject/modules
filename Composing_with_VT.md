**An example of a working environnement, using VT.**


You can find the patches in the downloads section :

http://code.google.com/p/vtmodules/downloads/detail?name=VT_Composer_framework.zip&can=2&q=#makechanges


The main folder is composed as follow :

./

/fx            → contains the effects abstractions to patch up custom fx chains.

/mixstrip      → contains the abstractions for the mixing desk (thanks .mmb).

/rec           → contains the recording abstraction, that's were you should export your audio.

Track.pd       → a patch loading Visual Tracker hooked-up to the mixing desk.

/visualtracker  → the Visual Tracker folder you can download at the parent google code.

To start composing you just need to open Track.pd, and start loading modules. You can save the mixing-desk settings, and effects patching, by just “save-as” the patch with a new name. But you need to be carefull not to save visualtracker abstraction when quitting – save just your patch. If you're bother with the question do as follow when quitting :
1- save you composition with the save option of Visual Tracker.
2- clear you composition.
3- save your patch.
4- quit.