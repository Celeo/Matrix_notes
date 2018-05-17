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

Fading is the sprite's hits (minimum 2), where the fading is physical if the sprite's level is greater than your resonance.

### Decompile sprite

> Action type: **Complex** \
> Test: `Decompiling + RES [level] v. sprite level (+ compiler's RES)`

Attempt to decompile a sprite. This is used offensively; a sprite's compiler can just dismiss it with a simple action.

Fading is the sprite's hits (minimum 2), where the fading is physical if the sprite's level is greater than your resonance.

### Kill complex form

> Action type: **Complex** \
> Test: `Software + RES [level] v. complex form level + RES`

Attempt to kill a complex form sustained by another resonance being. Net hits each reduce the hits on the original threading test. If that value goes to 0, the complex form ends.

Fading is equal to as if the complex form has been threaded by you originally.

### Register sprite

> Action type: **Complex** \
> Test: `Registering + RES [level] v. sprite level * 2`

Attempt to register a sprite, where the level is up to your resonance * 2.

Fading is the sprite's hits (minimum 2), where the fading is physical if the sprite's level is greater than your resonance.

### Thread complex form

> Action type: **Complex** \
> Test: `Software + RES [level] v. special`

Attempt to thread a complex form, where the level is up to your resonance * 3. This is affected by noise, the target being on another grid, and the public grid's limitations. You can only use complex forms that require a target against an icon you've spotted.

Sustaining a complex form penalizes the technomancer with a -2 dice pool modifier to all actions per complex form being sustained. If you're interrupted, you may have to perform a `Resonance + WIL v. 2` test to continue sustaining complex form(s). If you fall unconscious, all your complex forms end.

The fading for this action is dependent on the complex form selected and the level it was attempted at (minimum 2). If you get more hits on the test than your resonance, the damage is physical (otherwise stun).

## Fading

The penality for using resonance actions. Resist with `RES + WIL`. This damage cannot be healed; you have to sleep it off.
