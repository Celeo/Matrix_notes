# Matrix actions

Any action that is limited by Data Processing (DataP) or Firewall can be done on a commlink and are generally legal. Any action that is limited by Attack or Sleaze can only be done on a device (or TM persona) with those attributes, and are generally illegal.

## Brute force

> Action type: **Complex** \
> Marks required: **None** \
> Test: `Cybercombat + LOG [Attack] v. Firewall + WIL`

"Loud and proud" way of getting a mark on a target. Success means the target is alerted, and you also do 1 DV of Matrix damage for every 2 complete net hits in the test. Failure means, per normal Attack rules, you 1 box of unresisted Matrix damage per opponent's net hit. This can be performed in an attempt to place 2 marks at a -4 and 3 at -10.

This can also be used to hop grids, with a test threshold of 4 for a local grid and 6 for a global grid. A successful test *does not* alert anyone.

## Change icon

> Action type: **Simple** \
> Marks required: **4** \
> Test: **none**

Change the target's icon.

## Check overwatch score

> Action type: **Simple** \
> Marks required: **None** \
> Test: `EWar + LOG [Sleaze] v. 6`

Know your OS before this test.

## Control device

> Action type: **Complex** \
> Marks required: **depends** \
> Test: **depends**

Force a device to take an action. Test dice pool mirrors that of taking the action normally. The limit of this test is the limit of the test normally, or DataP, whichever is lower. If there is no associated test, make a `EWar + INT [Sleaze] v. Firewall + INT` test. The type of this action is the same as making the action normally, and requires 1 mark for a Free action, 2 for Simple, and 3 for Complex.

This can be used to control multiple devices at once. If you have 4 marks on each, there is no additional test. If you don't, then you must split the test pool into a number of groups equal to the number of devices you want to control.

## Crack file

> Action type: **Complex** \
> Marks required: **1** \
> Test: `Hacking + LOG [Attack] v. Protection rating * 2`

Remove encryption from a file.

## Crash program

> Action type: **Complex** \
> Marks required: **1** \
> Test: `Cybercombat + LOG [Attack] v. Firewall + INT`

Crash target program. You must target a specific program that you know is running. If successful, the target program ends and cannot be restarted until the device it was running on is rebooted.

## Data spike

> Action type: **Complex** \
> Marks required: **None** \
> Test: `Cybercombat + LOG [Attack] v. Firewall + INT`

Attack the persona/device. This action's DV is equal to your (Attack rating) + (1 * net hits) + (2 * marks on target). Resist damage per usual with `Device rating + Firewall`.

## Disarm data bomb

> Action type: **Complex** \
> Marks required: **None** \
> Test: `Software + INT [Attack] v. Data bomb rating * 2`

Disarm the bomb. Failure means it explodes, dealing its damage to you an potentially destroying the file (as determined by whoever set the bomb).

## Edit file

> Action type: **Complex** \
> Marks required: **1** \
> Test: `Computer + LOG [DataP] v. Firewall + INT`

Create / change / copy / delete a file. Using this action to *change* the file allows changing 1 paragraph of text, 1 image detail, or 3s of audio/video.

Trying to copy a file with protection automatically fails. Trying to copy a file with a data bomb sets off the data bomb.

Successfully copying a file makes you the owner of the copy.

If you use this action to perform an ongoing edit, perform this action once, and spend one complex action per combat turn to maintain the modification.

You can also encrypt a file with this test on a file you own without the opposed test, with the number of hits becoming the rating of the protection.

## Enter or exit host

> Action type: **Complex** \
> Marks required: **1** \
> Test: **none**

Enter a host you have a mark on, or leave the host you're in.

## Erase mark

> Action type: **Complex** \
> Marks required: **depends** \
> Test: `Computer + LOG [Attack] v. Firewall + WIL`

Erase another's mark. You require 3 marks on the icon that the mark is on. You can try to erase 2 marks at a -4 or 3 at -10, but all marks must be on the same target and from the same source.

## Erase Matrix signature

> Action type: **Complex** \
> Marks required: **none** \
> Test: `Computer + RES [Attack] v. Signature rating * 2`

Erase a Matrix signature. Requires having Resonance, but this is a Matrix action.

## Format device

> Action type: **Complex** \
> Marks required: **3** \
> Test: `Computer + LOG [Sleaze] v. Firewall + WIL`

Next time the device shuts down, it doesn't boot back up until an Extended `Software + LOG [Mental]` test is made.

## Full Matrix defense

> Action type: **Interrupt** \
> Marks required: **4** \
> Test: **none**

Boost your defense. Add your Willpower to defense tests against Matrix actions (even if your Willpower is already in the test). Reduce your initiative by 10. This bonus lasts for the rest of the combat turn.

## Grid hop

> Action type: **Complex** \
> Marks required: **none** \
> Test: **none**

Hop to another grid you have access to.

## Hack on the fly

> Action type: **Complex** \
> Marks required: **none** \
> Test: `Hacking + LOG [Sleaze] v. Firewall + INT`

The sneaky version of Brute Force. Instead of dealing damage alongside the marks on a success, this action gives one hit on Matrix perception test for every 2 net hits. Unsuccessfully using this to hop grids does not alert anyone.

## Hide

> Action type: **Complex** \
> Marks required: **none** \
> Test: `EWar + INT [Sleaze] v. DataP + INT`

Specified target that does not have a mark on you loses you and must perform a Matrix perception test to find you (assuming you're running silent or > 100m away).

## Invite mark

> Action type: **Simple** \
> Marks required: **4** \
> Test: **none**

Invite a target to place a specified number of marks on an icon you own for a specified amount of time, after which the target can use a Free Action to place the marks. This offer can be revoked up until the target places the mark(s).

## Jack out

> Action type: **Simple** \
> Marks required: **4** \
> Test: `Hardware + WIL [Firewall] v. Attack + LOG`

Leave the Matrix and reboot your device. Being in VR when taking this action forces dumpshock. You only need to make the test if you're linked-locked, and the test is against each icon that is sustaining the link-lock (compare your hits against the hits of each).

## Jam signals

> Action type: **Complex** \
> Marks required: **4** \
> Test: `EWar + LOG [Attack]`

Device becomes a jammer until you cancel the effect or use it for something else. Add noise equal to the hits within 100m.

## Jump into rigged device

> Action type: **Complex** \
> Marks required: **3** \
> Test: `EWar + LOG [DataP] v. Firewall + WIL`

Jump into a device that has a rigger adaptation with your control rig. The test is only required if you are not the owner of a device and the owner has not given you permission to do so. This cannot be performed against a device that someone else is jumped into.

## Matrix perception

> Action type: **Complex** \
> Marks required: **none** \
> Test: `Computer + INT [DataP] v. Sleaze + LOG`

Look around in the Matrix. The opposed test is for icons running silent within 100m.

### Spotting

* If your target is not running silent and
    * Is a host: automatic spot
    * Is within 100m: automatic spot
    * Is outside 100m: `Comp + INT [DataP]`
* If yout target is running silent and
    * Is a host: `Comp + INT [DataP]`
    * Is within 100m: `Comp + INT [DataP] v. Sleaze + LOG`

Targets you have marks on are automatically spotted, no matter the distance, without a test.

Non-host targets running silent outside of 100m cannot be detected.

Any non-mark icon can run silent.

To detect if there even are icons running silent within 100m, spend a hit on a Matrix perception (`Comp + INT [DataP]`) test. To find a specific icon running silent once you know one exists, you have to make the oppposed Matrix perception (`Comp + INT [DataP] v. Sleaze + LOG`) test, and you randomly find one icon running silent that you won the test against.

*Note*: homerules usually allow to *filter* which hidden icon you're looking for before you are given a random one.

## Matrix search

> Action type: **Special** \
> Marks required: **none** \
> Test: `Computer + INT [DataP]`

Search for information on the Matrix. The duration of the test and threshold depend on availability and the search area, respectively. Hits above the threshold can be used to reduce the search time: divide the base time by the extra hits to calculate the reduction. Failure to meet the threshold means that you still spent the time looking.

Information stored in a host requires you to enter the host before performing this action.

### Threshold and duration

| Information is | Threshold | Time |
| --- | --- | --- |
| General or public | 1 | 1 min |
| Limited or not publicized | 3 | 30 min |
| Hidden or actively erased | 6 | 12 hours |
| Protected or secret | n/a | n/a |

### Modifiers

| Information is | Pool modifier |
| --- | --- |
| Intricate or specialized | -1 |
| Obscure | -2 |
| On another grid | -2 |

## Reboot device

> Action type: **Complex** \
> Marks required: **3** \
> Test: `Computer + LOG [DataP] v. Firewall + WIL`

Reboot the target device. It comes back online at the end of the next combat turn. If the device housed a persona, that persona has its OS reset to 0 and all marks it placed and those that are on it are erased. If a metahuman was using the device in VR, they suffer dumpshock. When the device comes back on, it connects to any grid that it has access to, falling back to the public grid. When making this action, select an amount of time to have the device be offline. It can be physically turned back on in the meantime, bringing it online at the end of the next combat turn.

This does not work on hosts, Technomancers, or sprites, and the only *persona* it works on is yours. This action fails on a device that is link-locked.

## Send message

> Action type: **Simple** \
> Marks required: **0 or 1** \
> Test: **none**

Send text the length of a short sentence, an image, or a file to a user whose commcode you know. If you're using the Matrix through a DNI, even in AR, you can send up to a paragraph of text. This can also be used to open a live feed to any number of recipients from any recording devices you have.

## Set data bomb

> Action type: **Complex** \
> Marks required: **1** \
> Test: `Software + LOG [Sleaze] v. Device rating * 2`

Set a data bomb on a file. Select the desired rating of the bomb when you do so, up to the net hits on your test, select the passcode to bypass it, and select whether or not the bomb will delete the file it's attached to if it detonates. Only one bomb can be on a file at a time. Using the passcode to bypass the detonation does not remove the bomb; it just allows access to the underlying file. Data bombs deal damage equal to their rating in dice to an unauthorized user, are themselves removed, and the file (if configured to do so) is also removed.

## Snoop

> Action type: **Complex** \
> Marks required: **1** \
> Test: `EWar + INT [Sleaze] v. Firewall + LOG`

Intercept Matrix traffic to and from the target as long as you have them marked. This data can be viewed as it happens or saved for later on some storage medium.

## Spoof command

> Action type: **Complex** \
> Marks required: **1** \
> Test: `Hacking + INT [Sleaze] v. Firewall + LOG`

Spoof a command from your marked icon to another (potentially unmarked) device/agent (not persona/IC/sprite/host/file). The target makes the defense test, not the owner you're spoofing.

## Switch interface mode

> Action type: **Simple** \
> Marks required: **4** \
> Test: **none**

Switch between AR and VR. You cannot switch another's mode. You cannot switch if you are link-locked.

## Trace icon

> Action type: **Complex** \
> Marks required: **2** \
> Test: `Computer + INT [DataP] v. Sleaze + WIL`

Trace an device or persona to its physical location. You know their location as long as you have them marked.
