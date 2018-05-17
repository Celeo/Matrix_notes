# Sprite types and powers

## Powers

### Camouflage

> Test: **none**

Hide a file in another. The original file then requires a Matrix perception test to find it, and the searcher must know that it exists beforehand (including the sprite itself).

### Cookie

> Test: `Hacking + RES [Sleaze] v. Firewall + INT`

Tag a persona with a file that tracks their activities: entering and exiting hosts, communications (when and with whom, but not content), and programs they use, etc. This file is running silent and protected with a rating equal to the sprite's level. The net hits on the tests determine the level of detail: 1 being bare and 4+ being a detailed report. This lasts for a length of time determined when the test was made, after which the file returns to the sprite (if the sprite isn't in the Matrix at the time, the file is deleted), where it can be handed off to a technomancer.

Removing a cookie is the same for any hidden and protected file: Matrix perception to look for hidden files, then spend hits to find *this* hidden file, then decryption, then deletion.

### Diagnostics

> Test: `Hardware + Level [DataP]`

Perform a teamwork test with someone using or repairing a device. Any net hits means the user gets a +1 limit, and net hits each add one die to the person making the test. This lasts until the sprite does something else.

### Electron storm

> Test: `Cybercombat + RES [Attack] v. Firewall + INT`

Surround the target in a storm of resonance. This deals DV equal to the sprite's resonance in Matrix damage (resisted normally) upon a succesful test and each of the sprite's actions to sustain it thereafter, and the target takes +2 noise for the duration. This ends if the sprite takes damage or ends the power.

### Gremlins

> Test: `Hardware + Level [Attack] v. Firewall + Rating`

Causes a device to glitch, or critical glitch if the test yields 4+ net hits.

### Hash

> Test: **none**

Temporarily protect a file so that only the sprite can access it for up to its level in combat turns. When the powr stops, the file is reverted to its previous state, except for if the sprite is destroyed while sustaining, in which case the file is not reverted, meaning it is mangled beyond use.

### Stability

> Test: **none, requires a mark on the device/persona**

Prevents glitches and turns critical glitches into regular glitches on the device or persona while the sprite sustains it.

### Suppression

> Test: **none, requires the sprite being in a host**

Delays a host launching IC for level / 2 combat turns while this power is sustained.

### Watermark

> Test: **none**

Leaves a permanent (though erasable) resonance mark on a file.

## Types

All sprites have the Computer skill and have initiative dice of 4D6.

| Name | Attack | Sleaze | DataP | Firewall | Initiative base | Skills | Powers |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Courier | L | L+3 | L+1 | L+2 | (L*2)+1 | Hacking | Cookie, Hash |
| Crack | L | L+3 | L+2 | L+1 | (L*2)+2 | EWar, Hacking | Suppression |
| Data | L-1 | L | L+4 | L+1 | (L*2)+4 | EWar | Cookie, Watermark |
| Fault | L+3 | L | L+1 | L+2 | (L*2)+1 | Cybercombat, Hacking | Electron Storm |
| Machine | L+1 | L | L+3 | L+2 | (L*2)+3 | EWar, Hardware | Diagnostics, Gremlins, Stability |

* Courier sprites are for delivering messages and tracking
* Crack sprites are for hacking, especially in hosts
* Data sprites are for getting information
* Fault sprites are for combat
* Machine sprites are for boosting or crashing devices
