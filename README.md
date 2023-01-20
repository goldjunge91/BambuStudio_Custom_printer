# BambuStudio_Custom_printer

my configs for BambuStudio Custom Printer

## the "third party printer demo preset are from her --> [wiki](https://wiki.bambulab.com/en/software/bambu-studio/add-third-party-printer-in-studio)

_**(i install BambuStudio standard windows folder: "C:\Program Files\Bambu Studio"**_
**Importend Directorys:**
_...\Bambu Studio\resources\profiles_
_...\Bambu Studio\resources\web\image\printer_
for Troubleshot
_...\AppData\Roaming\BambuStudio\system_

### How To

1. Copy the folder "**Anycubic**" & the File "**Anycubic.json**"  to "**C:\Program Files\Bambu Studio\resources\profiles**" (if you have like me the standard windows folder you can use my string)
2. Copy "**Anycubic I3Mega_cover.png**" to "**C:\Program Files\Bambu Studio\resources\web\image\printer**"
3. finished.

### Troubleshoot

If you have any trouble to open after this BambuStudio then follower this;

1. go to "**C:\Users\"your username"\AppData\Roaming\BambuStudio\system**"

or

Click **Start**, go / type to **Run**, type in **%appdata%**, and press Enter Press Win+R, type in %appdata%, and press Enter
(copy from: <https://superuser.com/a/1039202>)

_you have to find Appdata/Roming folder._

2. then Remove Anycubic folder and Anycubic.json
3. Done run BambuStudio

## for Changes on the Stock Parameter

in Case you want to make changes to the printer settings
Print area: Anycubic I3Mega 0.4 nozzle.json search "printable area":[ her you can change your size
Machine settings: fdm_Anycubic_common.json


###License 

feel free to share modify and copy

GNU General Public License v3.0