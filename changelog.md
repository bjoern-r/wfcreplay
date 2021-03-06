Changelog
=========


WfcReplay v0.5 - 26 May 2014
----------------------------
This version uses a whole new ASM URL patcher that produces much smaller codes. As a result, games that previously did not have suitable code caves are now compatible, such as Pok�mon Black 2 & White 2.

* URL patcher now uses compressed string addresses.
* Various other URL patcher optimizations.


WfcReplay v0.4.1 - 25 May 2014
------------------------------
Fixes an issue introduced in the previous version when using games with uncompressed ARM9 binaries or overlays.

* Fixed "BLZ decompression failed" error when ARM9 binary or overlay is not compressed.


WfcReplay v0.4 - 25 May 2014
----------------------------
This release contains various bugfixes for a number of games, such as Zelda: Phantom Hourglass and Planet Puzzle League. It also corrects some other issues. Antipiracy-protected games remain unsupported.

* Fixed code output issue for games with invalid characters in their title IDs, fixes various games.
* Fixed code cave address alignment issue, fixes various games.
* Fixed "Could not find ARM9 hook" error when the temporary folder path contained spaces.
* Fixed crash when no HTTPS URLs were found.


WfcReplay v0.3 - 23 May 2014
----------------------------
Initial release.