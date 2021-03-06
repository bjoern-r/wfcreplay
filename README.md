﻿WfcReplay
=========
WfcReplay is a command-line Windows utility written in C# that automatically generates an Action Replay DS code for a Nintendo DS game that will make it use HTTP instead of HTTPS for connections to Nintendo Wi-Fi Connection. This is done by pre-finding all URLs in the ROM and patching them in-memory. This can be used to connect to any custom Nintendo Wi-Fi Connection server.

To run this program, the .NET Framework 4.0 or higher must be installed on your computer.

NOTE: Older versions of DeSmuME are incompatible with codes generated by WfcReplay. Use a newer version of DeSmuME based on r5047 or later, or try an alternative patching method.

Usage
-----
```
WfcReplay.exe rompath
```

To use WfcReplay, pass it the file path of an NDS ROM. You can also drag-and-drop the ROM file onto the WfcReplay executable. WfcReplay will then analyze the ROM and produce a text file containing the Action Replay DS code, which will be written to the current working directory.

Compatibility
-------------
WfcReplay should work with all NDS games, though not every single one of them has been tested. If you find an incompatible game, please create an issue on the GitHub page at https://github.com/Prof9/wfcreplay.

Notes
-----
* Action Replay DS codes generated by WfcReplay may interfere with certain Action Replay DS codes from other sources, such as cheat database.
* Furthermore, the code may disrupt anti-anti-piracy features of older flashcards. These flashcards are not intended to be supported.
* Additionally, for certain games the code may clash with special flashcard features like soft-reset. If this happens, disable these features.

Credits
=======
**WfcReplay (c) 2014**

* Prof. 9

**BLZ (c) 2011**

* CUE

License
=======
This project is licensed under the terms of the MIT license. See *license.txt* in the main folder for more information.

WfcReplay includes BLZ v1.4 by CUE, which is covered by the GPLv3 license. As such, the source code for this program is included and can be found in *blz.c*. The full terms of the license can be found in *license.txt* in the *BLZ* folder.
