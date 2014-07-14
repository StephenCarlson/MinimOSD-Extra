MinimOSD-Extra
==============

My Fork of the Minimosd-extra project. My additions are m/s units and a better variometer




Critical Notes:

This folder contains the code that was labeled r793 on the Google Code SVN page for Minimosd-extra. I did not fork from any of the several MininOSD's on GitHub.

The CT Config Tool program didn't succeed in uploading the Custon Charset to the board. I tried enabling the Font.ino segment in the code, and also tried the special sketch in the Tools folder that comes with the SVN mirror, neigher succeeded. I ended up loading an older (like r710-ish) version on the board and used that to upload the custom character set.

The .jar file in the said Tools folder is awesome for editing the character set. I was going to brute-force stuff until I stumbled on it.

Disabled the Callsign time-cycle thing, and disabled its persistance on all panels.

The Variometer feature is now more than just a vertical speed: It now has a 5-state icon with assignable thresholds.

