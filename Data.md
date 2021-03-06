# Device ratings

| Type | Rating | Examples
| --- | --- | --- |
| Simple | 1 | General appliances, public terminals, entertainment systems |
| Average | 2 | Standard personal electronics, basic cyberware, vehicles, drones, weapons, residential security devices |
| Smart | 3 | Security vehicles, alphaware, corporate security devices |
| Advanced | 4 | High-end devices, betaware, military vehicles and security devices |
| Cutting Edge | 5 | Deltaware, credsticks, black-ops vehicles and security devices |
| Bleeding edge | 6 | Billion-nuyen experimental devices, space craft |

---

# User modes

| Name | Initiative | Inititiave Dice | Notes |
| --- | --- | --- | --- |
| AR | Same as physical | Same as physical | Physical perception -2 |
| Cold-sim VR | DataP + INT | 3D6 | |
| Hot-sim VR |  DataP + INT | 4D6 | +2 to all Matrix actions |

The +2 granted by **Hot VR** only applies to *Matrix actions*, not Resonance actions or defense tests.

---

# Agents

Autonomous programs. Are rated from 1 to 6. Running an agent requires a program slot on a cyberdeck. Agents use the deck's Matrix attributes, their rating for (standard) attributes, and Computer/Hacking/Cybercombat skills equal to their rating. Agents can also use other running programs on the deck. Agents use the deck's Matrix condition monitor, and don't have their own OS, but do have their own persona and icon.

---

# Noise

## From distance

| Distances | Level |
| --- | --- |
| Direct connection | 0 |
| <= 100m | 0 |
| <= 1km | 1 |
| <= 10k | 3 |
| <= 100km | 5 |
| >= 100km | 8 |

## From obstacles

| Situation | Level |
| --- | --- |
| Dense foliage | 1 per 5m |
| Faraday cage | Totally blocked |
| Fresh water | 1 per 10cm |
| Jamming | 1 per hit on Jam Signals Matrix action |
| Metal-laced earth or wall | 1 per 5m |
| Salt water | 1 per 1cm |
| Spam zone / static zone | Rating |
| Wireless negatation | Rating |

### Spam and static zones

| Spam | Static | Level |
| --- | --- | --- |
| City downtown | Abandoned building | 1 |
| Sprawl downtown | Abandoned neighborhood, barrens | 2 |
| Major event / advertising blitz | Rural area, abandoned underground area, heavy rain/snow | 3 |
| Commercial area in a city | Wilderness, severe storm | 4 |
| Commercial area in a sprawl | Remote place with satellite access only | 5 |
| Massive gathering or during widespread emergency | Remote, enclosed place (cave / desert ruin) | 6 |

## Directly connected

When devices that are physical connected to each other (e.g. cyberdeck to camera), tests are made without penalties from noise. When a device is being hacked like this, the device rolls its defense without any benefit from any PAN/WAN.

---

# Hosts

Hosts are cloud computing, spread over the entire globe on a specific grid. Hosts are reachable without noise penalties from distance. When inside a host, you can communicate with other icons inside the host without noise from distance as all devices are considered directly connected to each other. When inside, you cannot control icons outside the host (sending messsages is fine), and the inverse is true. Hosts have IC and often have Matrix security personnel called spiders.

## Archives

Hosts can store files in archives, where it cannot (for the most part) be accessed by hackers. A *registered* user must fetch the file from the archive.

## Attributes

Hosts all have a rating from 1 to 12. They also have the four Matrix attributes, which are ranked at rating, rating + 1, rating + 2, and rating + 3, where the assignment is selected by the host itself. These attributes are shared by all of the host's IC.

## Convergence

OS continues to climb while inside a host (assuming you've done something illegal or do so while inside). When you hit the limit, the host gets 3 marks on you and starts launching IC. If you exit the host, GOD converges on you, so jack out from inside the host.

## Accessing

To get inside a host, a persona requires a mark on the host. This are distributed to valid users automatically, but hackers without this invitation require getting a mark on their own. This is done in the standard way, rolling against the host's attributes. Once the hacker has a mark on the host, they can enter the host without another test.

## IC

Each IC program has a persona with its own condition monitor and initiative score, and is in hot-sim VR. IC use the Matrix attributes of their host. The host and IC share marks, so if a hacker gets a mark on one IC program, the hacker gets marks on all IC programs and the host itself, but the opposite is also true for spotting hackers.

A host can launch 1 IC per combat turn, at the start, can have its rating in active IC running at any time, and can't launch more than 1 of any single type at once. Destroying an IC program means the host will likely launch it at the start of the next combat turn.

The only IC running 24/7 usually is Patrol IC.

### Types

All IC have an attack of `Host rating * 2 [Attack] v. Firewall + WIL` except for Patrol IC, which doesn't have an attack.

#### Acid

When it gets 1 or more net hits on an attack, it lowers your Firewall by 1 (cumulative). If your Firewall is 0 and it gets another net hit, it causes 1 DV of damage per net hit. Firewall reduction lasts until you reboot.

#### Binder

Same as Acid but for Data Processing.

#### Black

On a hit, it link-locks you and causes damage equal to (Attack rating) + (1 * net hit) + (2 * marks) **along with** and equal amount of biofeedback damage.

#### Blaster

Like Black IC, but the biofeedback damage is only stun.

#### Crash

On a hit where it has you marked, one of your programs (at random) crashes.

#### Jammer

Like Acid and Binder IC, but for Attack.

#### Killer

Like Blaster, but no biofeedback damage - just the Matrix damage.

#### Marker

Like Acid/Binder/Jammer but for Sleaze.

#### Patrol

Uses Matrix perception actions to look for personas making illegal actions inside the host.

*Note*: Once you're inside a host, you're legally there, until you do something illegal.

#### Probe

Gets another mark on the target on a hit (up to 3; marks are shared amongst the host and all IC).

#### Scramble

If it hits when the host has 3 marks on you, you are forcibly rebooted.

#### Sparky

Like Blaster, but without link-locking.

#### Tar baby

Link-locks on a hit, unless you're already link-locked, in which case it gets a mark on you.

#### Track

If it hits and has 2 or more marks on you, the host and its owners get your physical location.

---

# Programs

## Commlink apps

These apps are legal to own and use and can be used on commlinks. Commlinks can run a number of these apps equal to its device rating / 2, rounded up.

### AR Games

Games.

### Diagnostics

Gives vital statistics on all devices in the commlink's PAN. Works like a biomonitor for the PAN, altering the user to attacks.

### P2.1

Social networking.

### Theme music

Music based on the PAN's devices' stats.

### Ticket

An RSS feed of a specific topic. Halves Matrix search actions for that topic.

## Common programs

These programs are legal to own and use.

### Browse

Halves Matrix search time.

### Configurator

When you run this program, create an alternate Matrix attribute configuration for your deck. On your next reconfigure action, you may select this full configuration to switch to.

### Edit

Adds 2 to the DataP limit for any edit tests.

### Encryption

+1 to Firewall.

### Signal scrub

Rating 2 noise reduction.

### Toolbox

+1 to DataP.

### Virtual machine

Run 2 additional programs but take an unresisted extra box of Matrix damage whenever you take Matrix damage.

### Bootstrap

Allows the "format device" Matrix action to also set up commands that will run when the device next boots, like announcing its location, reconfiguring its Matrix attributes (if cyberdeck), recording actions taken, or spamming the user.

### Search

+2 DP to Matrix search actions when looking for data on the host that contains that data.

### Shredder

+2 to DataP when deleting a file. Files deleted like this (or by data bombs) are mangled, and recovering them requires constant access to the grid or host that it originated in, and a `Computer + Logic [Metal]` extended test (18, 1 week).

## Hacking progarms

These programs are illegal to own or use.

### Armor

+2 DP to resist Matrix damage.

### Baby monitor

Freely check your OS.

### Biofeedback

When you cause Matrix damage, the target also takes an equal amount of biofeedback damage (assuming they are biological) which is either stun if they are in AR or cold-sim VR, or physical if they are in hot-sim VR. This applies to your failed Attack Matrix actions.

Biofeedback damage is resisted by `Firewall + WIL`.

### Biofeedback filter

+2 DP to resist biofeedback damage.

### Blackout

Like the Biofeedback program, but is always stun damage.

### Decryption

+1 to Attack.

### Defuse

+4 DP to resist damage from data bombs.

### Demolition

+1 rating to data bombs you place.

### Explorit

+2 to Sleaze when performing a "hack on the fly" Matrix action.

### Fork

Perform a single Matrix action against 2 targets. You roll your test once, both targets defend separately.

### Guard

Reduce damage you take from marks by 1 per mark.

### Hammer

Whenever you cause Matrix damage against anything other than you, deal the damage + 2.

### Lockdown

Whenever you cause damage to a persona, they are link-locked until you stop running this progarm.

### Mugger

Deal 1 bonus damage per mark.

### Shell

+1 to resist Matrix damage and biofeedback damage. This stacks with other programs.

### Sneak

+2 DP to defend against Trace User. Convergence while this is running will prevent the demiGOD from getting your physical location.

### Stealth

+1 to Sleaze.

### Track

+2 to DataP when making Trace User tests. If the target is running a Sneak program, this program *instead* cancels that bonus.

### Wrapper

Allows you to change icons you own to anything, regardless of the standard Matrix rules on iconography limits.

### Cat's paw

When performing "data spike" Matrix actions, instead of doing damage, the target is spammed with popups and distracting images, imposing upon the target a negative DP of 2 + number of marks. Marks added or removed after this action will modify the penalty.

### Cloudless

Allows using an "edit file" Matrix action to remove a file from the Matrix and store it offline only. This test is `Computer + LOG [DataP]` where the threshold is 6 for the public grid, 8 for a local grid, and 10 for a global grid.

### Crash

+2 to DataP when attempting a "reboot device" Matrix action.

### Detonator

When setting a data bomb with this program running, the user can delay the explosion of the bomb until a specified number of actions have been taken against the file. Data bombs set with this program can also *just* delete the file. These special data bombs have a device rating of 3 and Sleaze equal to the number of remaining actions - 1 when tested against a Matrix perception action.

### Evaluate

Estimates how much some paydata might be worth.

### Fly on a wall

While running and the decker is only performing Matrix perception actions, their OS only raises by 1D6 every 30 minutes. Requires activation with a hide action.

### Hitchhiker

Allows taking non-hacker friends into foundations and UV hosts.

### Nuke-from-orbit

Files deleted with this program running a permanently deleted from the Matrix. OS from the opposed test is doubled. Offline backups and the resonance realms are the only way to retrieve this information.

### Paintjob

+2 to Attack when attempting a "erase mark" Matrix action.

### Smoke-and-mirrors

Increase Sleaze by 1 to 5 while also being subject to the same amount of noise. This noise also applies to "trace icon" tests performed against the deck, but has no impact on convergence.

### Swerve

+1 to Firewall when resisting a "reboot device" Matrix action.

### Tantrum

Causes "data spike" Matrix actions to forgo dealing damage and instead causing nausea in the target (cold/hot-sim deckers, all technomancers) for 3 combat turns.

### Tarball

+2 to Attack and +1 DP to "crash program" Matrix actions, but the user cannot select which program is being targeted.

---

# Matrix actions

Any action that is limited by Data Processing (DataP) or Firewall can be done on a commlink and are generally legal. Any action that is limited by Attack or Sleaze can only be done on a device (or TM persona) with those attributes, and are generally illegal.

## Brute force

> Action type: **Complex** \
> Marks required: **None** \
> Test: `Cybercombat + LOG [Attack] v. Firewall + WIL`

"Loud and proud" way of getting a mark on a target. Success means the target is alerted, and you also do 1 DV of Matrix damage for every 2 complete net hits in the test. Failure means, per normal Attack rules, you 1 box of unresisted Matrix damage per opponent's net hit. This can be performed in an attempt to place 2 marks at a -4 and 3 at -10.

This can also be used to hop grids, with an opposed test DP of 4 for a local grid and 6 for a global grid. A successful test *does not* alert anyone.

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

> Action type: **Simple** \
> Marks required: **1** \
> Test: `Cybercombat + LOG [Attack] v. Firewall + INT`

Crash target program. You must target a specific program that you know is running. If successful, the target program ends and cannot be restarted until the device it was running on is rebooted.

## Data spike

> Action type: **Simple** \
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
> Test: `Extended Computer + INT [DataP]`

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

## Garbage in/garbage out

> Action type: **Complex** \
> Marks required: *3** \
> Test: `Software + LOG [Sleaze] v. Firewall + LOG`

Confuse the input and output commands of a device, remapping a single input to a single output. For example, a smartgun, when issued the fire command via DNI or the trigger, instead ejects the magazine, an elevator could go to the top floor instead of the lobby, or which group is targeted in a friend-or-foe system. Fixed by a reboot.

## Traceback

> Action type: **Special** \
> Marks required: **4** \
> Test: `Extended Computer + INT [DataP], 30 min`

Cannot be performed inside a host. Requires having found a mark on a device you own, you trace the mark back to its owner's physical location. Requires hits of 10 + mark owner's Sleaze (reconfiguration updates the hits required). If the persona is running silent, the trace gets back to their vicinity.

---

# Organized

## By function

| Device manipulation | Type |
| --- | --- |
| Control device | Variable |
| Format device | Complex |
| Reboot device | Complex |
| spoof command | Complex |

| File manipulation | Type |
| --- | --- |
| Crack file | Complex |
| Set data bomb | Complex |
| Disarm data bomb | Complex |
| Edit file | Complex |

| Information gathering | Type |
| --- | --- |
| Check overwatch score | Simple |
| Matrix perception | Complex |
| Matrix search | Special |
| Snoop | Complex |
| Trace icon | Complex |

| Mark manipulation | Type |
| --- | --- |
| Brute force | Complex |
| Erase mark | Complex |
| Hack on the fly | Complex |
| Invite mark | Simple |

| Matrix combat | Type |
| --- | --- |
| Crash program | Simple |
| Data spike | Simple |
| Full Matrix defense | Interrupt |

| Miscellaneous | Type |
| --- | --- |
| Change icon | Simple |
| Enter/exit host | Complex |
| Erase Matrix signature | Complex |
| Grid hop | Complex |
| Jack out | Simple |
| Jam signals | Complex |
| Jump into rigged device | Complex |
| Send message | Simple |
| Switch interface mode | Simple |

## By limit

| Attack | Type |
| --- | --- |
| Brute Force | Complex |
| Crack File | Complex |
| Crash Program | Complex |
| Data Spike | Complex |
| Erase Mark | Complex |
| Erase Matrix Signature | Complex |
| Jam Signals | Complex |

| Sleaze | Type |
| --- | --- |
| Check Overwatch Score | Simple |
| Crack File | Complex |
| Format Device | Complex |
| Hack on the Fly | Complex |
| Hide | Complex |
| Set Data Bomb | Complex |
| Snoop | Complex |
| Spoof Command | Complex |

| Data Processing | Type |
| --- | --- |
| Change Icon | Simple |
| Control Device* | Variable |
| Edit File | Complex |
| Enter/Exit Host | Complex |
| Grid Hop | Complex |
| Invite Mark | Simple |
| Jump Into Rigged Device | Complex |
| Matrix Perception | Complex |
| Matrix Search | Special |
| Reboot Device | Complex |
| Send Message | Simple |
| Switch Interface Mode | Simple |
| Trace Icon | Complex |

\* Control Device *might* be DataP, it depends

| Firewall | Type |
| --- | --- |
| Disarm Data Bomb | Complex |
| Erase Matrix Signature | Complex |
| Full Matrix Defense | Interrupt |
| Jack Out | Simple |

---

# Living persona

A technomancer's presence in the Matrix is represented by their living persona.

It differs from a decker's persona in the following ways:

* Matrix attributes are derived from the technomancer's mental attributes
* Matrix attributes cannot be reconfigured
* Cannot be a slave or master, or part of a PAN or WAN
* Cannot run programs
* Cannot use cold-sim VR
* Adds their Resonance to their dice pool to resist hot-sim addition tests
* Adds 2 dice to all Matrix perception tests
* No separate Matrix condition monitor

## Attributes

| Attribute | Source |
| --- | --- |
| Rating | Resonance |
| Attack | Charisma |
| Sleaze | Intuition |
| Data Processing | Logic |
| Firewall | Willpower |

## Rebooting

Rebooting is the technomancer's choice. They can stil select the duration that their persona is absent from the Matrix and override that before the time is up.

---

# Resonance actions

Resonance actions can only be performed by a **technomancer** and do not follow the regular rules of Matrix actions: no penalty for running silent, no bonus for hot-sim VR, no required mark total, and no OS accumulation.

## Resonance signatures

Signatures left behind by using a resonance action, visible to resonance beings (technomancers, sprites, etc.). The rating of the signature is equal to the rating of the entity that left it and lasts for that many hours. Finding a signature requires being a resonance being and getting 3 hits on a Matrix perception test, which comes in addition to the standard Matrix perception hits. If you've seen a signature before, you can recognize it again (potentially with a memory test). If you get 5 hits on a Matrix perception, you also get (also for free) an impression of what kind of ability or being left it. All resonance beings emit their unique signature on their being (with sprites sharing that of the technomancer that compiled it).

Leftover signatures can be erased with the "erase signature" Matrix action. The signature emitted by a resonance being (you or another) can be temporarily hidden for 1 combat turn per hit on "erase signature".

## Actions

### Call/dismiss sprite

> Action type: **Simple** \
> Test: **none**

Call a registered sprite to you, where it appears at the beginning of the next combat turn, or send a sprite back to the resonance, forfeiting any remaining tasks (performed on the sprite's next action).

### Command sprite

> Action type: **Simple** \
> Test: **none**

Command a sprite to do something.

### Compile sprite

> Action type: **Complex** \
> Test: `Compiling + RES [level] v. sprite level`

Compile a sprite.

Fading is 2x the sprite's hits (minimum 2), where the fading is physical if the sprite's level is greater than your resonance.

### Decompile sprite

> Action type: **Complex** \
> Test: `Decompiling + RES [level] v. sprite level (+ compiler's RES)`

Attempt to decompile a sprite. This is used offensively; a sprite's compiler can just dismiss it with a simple action.

Fading is 2x the sprite's hits (minimum 2), where the fading is physical if the sprite's level is greater than your resonance.

### Kill complex form

> Action type: **Complex** \
> Test: `Software + RES [level] v. complex form level + RES`

Attempt to kill a complex form sustained by another resonance being. Net hits each reduce the hits on the original threading test. If that value goes to 0, the complex form ends.

Fading is equal to as if the complex form has been threaded by you originally.

### Register sprite

> Action type: **Special** \
> Test: `Registering + RES [level] v. sprite level * 2`

Attempt to register a sprite, where the level is up to your resonance * 2.

Fading is the sprite's hits (minimum 2), where the fading is physical if the sprite's level is greater than your resonance.

This takes a number of hours equal to the sprite's level.

### Thread complex form

> Action type: **Complex** \
> Test: `Software + RES [level] v. special`

Attempt to thread a complex form, where the level is up to your resonance * 3. This is affected by noise, the target being on another grid, and the public grid's limitations. You can only use complex forms that require a target against an icon you've spotted.

Sustaining a complex form penalizes the technomancer with a -2 dice pool modifier to all actions per complex form being sustained. If you're interrupted, you may have to perform a `Resonance + WIL v. 2` test to continue sustaining complex form(s). If you fall unconscious, all your complex forms end.

The fading for this action is dependent on the complex form selected and the level it was attempted at (minimum 2). If you get more hits on the test than your resonance, the damage is physical (otherwise stun).

## Fading

The penality for using resonance actions. Resist with `RES + WIL`. This damage cannot be healed; you have to sleep it off. The minimum DV of fading is 2 for a resonance action.

---

# Complex form library

Complex forms that have a target of "device" can also be used on personas.

Complex forms that have a duration of "Permanent" must first be sustained for their level in combat turns before the effect becomes permanent.

The fading from threading a complex form is dependent on which form was used and the level it was used at, with a minimum of, as always, 2. This fading is physical if you get more hits than your resonance on the test, stun otherwise.

## Cleaner

> Target: **Persona** \
> Duration: **Permanent** \
> Fading: **L-2** \
> Test: `Software + RES [level]`

Reduce the target's OS by 1 per hit.

## Diffusion of X

> Target: **Device** \
> Duration: **Sustain** \
> Fading: **L-2** \
> Test: `Software + RES [level] v. Firewall + WIL`

Reduce one of the target's Matrix attributes by thet net hits, to a minimum of 1. This complex form must be taken separately per Matrix attribute.

## Editor

> Target: **File** \
> Duration: **Permanent** \
> Fading: **L-1** \
> Test: `Software + RES [level] v. DataP + INT`

Same as an "edit file" Matrix action, but does not require any marks.

*Note*: common interpretation of this rule is that it bypasses protection. There is disagreement about what it does with data bombs, with bypassing and copying them alongside the file being the 2 most popular interpretations.

## Infusion of X

> Target: **Device** \
> Duration: **Sustain** \
> Fading: **L-2** \
> Test: `Software + RES [level]`

The level of this complex form must equal or exceed the value of the attribute being affected. The attribute is increased by the number of hits, up to twice the attribute's normal value. This complex form must be taken separately per Matrix attribute. If the attribute being boosted is swapped, this complex form ends.

## Static veil

> Target: **Persona** \
> Duration: **Sustain** \
> Fading: **L-3** \
> Test: `Software + RES [level] v. threshold (1 or 2)`

The threshold of the test is 1 if the target is on the public grid, or 2 otherwise. The target's OS does not increase due to time while sustained.

## Pulse storm

> Target: **Device** \
> Duration: **Immediate** \
> Fading: **L-3** \
> Test: `Software + RES [level] vs. DataP + LOG`

Target is affected by noise equal to the net hits.

## Puppeteer

> Target: **Device** \
> Duration: **Immediate** \
> Fading: **L+1** \
> Test: `Software + RES [level] v. Firewall + WIL`

Getting a single net hit allows you to force the target to make a Free Action of your choice, with 2 for a Simple Action, and 3 for a Complex Action. The target performs the action as their next action.

## Resonance channel

> Target: **Device** \
> Duration: **Sustain** \
> Fading: **L-3** \
> Test: `Software + RES [level]`

The target's noise **from distance** is reduced equal to the net hits.

## Resonance spike

> Target: **Device** \
> Duration: **Immediate** \
> Fading: **L-3** \
> Test: `Software + RES [level] v. Firewall + WIL`

Target takes 1 DV of Matrix damage per net hit, unresisted.

Remember, this is a *resonance action*, not a *Matrix action*, so while the impact is real, the target literally won't know what hit them (assuming they're not a resonance being).

## Resonance veil

> Target: **Device** \
> Duration: **Sustain** \
> Fading: **L-3** \
> Test: `Software + RES [level] v. DataP + INT`

Matrix illusion. If the test is successful, even if the target believes it may be fake, they have to make a `Computer + INT [DataP] v. threshold` test where the threshold is your net hits to see through it.

## Static bomb

> Target: **Self** \
> Duration: **Immediate** \
> Fading: **L-1** \
> Test: `Software + RES [level] v. DataP + INT`

This test is made against all icons that have spotted you in one roll. Each icon you beat loses you. Any mark that has a mark on you is immune to this.

## Stitches

> Target: **Sprite** \
> Duration: **Permanent** \
> Fading: **L-3** \
> Test: `Software + RES [level]`

The sprite's Matrix condition monitor is replenished by the number of hits (to its natural maximum).

## Transcendent grid

> Target: **Self** \
> Duration: **Immediate** \
> Fading: **L-3** \
> Test: `Software + RES [level]`

You are counted as being on all grids and do not take the penalty from being on the public grid for 1 minute per hit.

## Tattletale

> Target: **Persona** \
> Duration: **Permanent** \
> Fading: **L-3** \
> Test: `Software + RES [level]`

Increase the target's OS by 1 per hit.

## Derezz

> Target: **Persona** \
> Duration: **Immediate** \
> Fading: **L-1** \
> Test: `Software + RES [level] v. Firewall + WIL`

Do 1 Matrix damage per hit and reduce the target's Firewall by 1 until it has rebooted. The Firewall reduction does not stack with any other applications of this complex form.

## FAQ

> Target: **Device or host** \
> Duration: **Permanent** \
> Fading: **L-3** \
> Test: `Software + RES [level], then (Immediate) Computer + INT + (level / 2) [level]`

Make the first test to activate the complex form, then make the second test. Works like a "Matrix search" test, with a threshold of 6 for truly obscure or long-forgotten information. This works only on a device the technomancer physically has or on a host.

## IC Tray

> Target: **Host** \
> Duration: **Immediate** \
> Fading: **L-3** \
> Test: `Software + RES [level] v. Sleaze + Rating`

Learn up to the hits in IC that the host is able to deploy.

## Redundancy

> Target: **Device** \
> Duration: **Sustain** \
> Fading: **L-3** \
> Test: `Software + RES [level]`

Grant temporary additional Matrix condition monitor boxes to the target for the duration.

## Misread marks

> Target: **IC** \
> Duration: **Permanent** \
> Fading: **L-1** \
> Test: `Software + RES [level]`

Tricks an IC program into thinking the technomancer's marks are its intended target, forcing it to ignore the technomancer for a number of Simple or Complex actions equal to the hits.

---

# Sprites

Digital creatures formed or summoned out of the resonance. In play, they are personas without devices, a jumble of code that shouldn't work but does. They are as smart as agents, which is not very. They cannot be parts of a PAN or WAN.

A compiled sprite starts with an OS of 0 and the OS increase due to time starts right away. If a sprite is converged upon, it is destroyed regardless of remaining tasks, and the demiGOD gets the sprite's technomancer's location (same with a "trace icon" test).

A sprite's device rating and resonance are both equal to is level, and its Matrix attributes are based on level and sprite type. It has a Matrix condition monitor of 8 + (level / 2) boxes. It's initiative is based on level and type.

A technomancer can only have 1 compiled sprit at a time.

A conscious technomancer always knows where their sprites are. If the technomancer goes unconscious, their sprites will finish the last action they were assigned. After this, compiled sprites will return to the resonance, tasks depleted, and registered sprites will hang out waiting for the technomancer.

## Tasks

The initial compiling test determines how many tasks the new sprite owns its technomancer - equal to the technomancer's net hits on the test.

## Registering

A compiled sprite can be registered on the Matrix to stick around longer and perform more intricate tasks. The "register sprite" resonance action takes a number of hours equal to the sprite's level, during which the sprite's OS does not increase from time, and neither it nor the technomancer can do anything else. Successful completion means the sprite is now registered and its OS is now 0.

A registered sprite's OS operates just like any hacker - it starts ticking only upon the first illegal action.

### Compiled tasks

* Single use of one of its powers (spend an additional task if you modify how it's being used)
* One combat turn worth of Matrix actions
* Participation in combat until it's over

Compiled sprites, upon completion of a remote task, return to the resonance.

### Registered tasks

* All tasks a non-register sprite can do
* Give a bonus of level in dice to learn a new complex form (single form)
* Give a bonus of level in dice to thread a complex form (single test)
* Sustain a complex form, taking the -2 penalty, for level of combat turns, upon which you either take the penalty yourself, spend another task, or let the complex form fade
* Perform a number of tasks given to another persona
* Return to the resonance, awaiting further instruction
* Re-register for more tasks

Compiled sprites, upon completion of a remote task, return to the technomancer.

---

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
| Data | L-1 | L | L+4 | L+1 | (L*2)+4 | EWar | Camouflage, Watermark |
| Fault | L+3 | L | L+1 | L+2 | (L*2)+1 | Cybercombat, Hacking | Electron Storm |
| Machine | L+1 | L | L+3 | L+2 | (L*2)+3 | EWar, Hardware | Diagnostics, Gremlins, Stability |

* Courier sprites are for delivering messages and tracking
* Crack sprites are for hacking, especially in hosts
* Data sprites are for getting information
* Fault sprites are for combat
* Machine sprites are for boosting or crashing devices

---

# Submersion

TODO
