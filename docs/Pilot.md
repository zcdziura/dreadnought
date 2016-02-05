Pilot
=====

The signature feature of Dreadnought's piloting capabilities is its autopilot system, which allows the user to create a custom path for the aethership to follow. No longer are you required to place shockwaves East and Northeast of the Vortex; you can put them anywhere, and the autopilot will be able to handle it!

Commands
--------

 - `pauto <on|off>` - Toggles the autopilot on and off
 - `pcall <on|off>` - Toggles siphon callout on or off. If enabled, the pilot will call out to siphon when sailing over a vortex.
 - `ppath <dir1> <dir2> <dir3>` - Creates the path that the autopilot will follow when hunting.

Pathing
-------

While it can be a bit confusing to think about at first, the autopilot's pathing command is fairly easy to understand. Say you have your shockwaves arranged in the following fashion:

```
      [*]
    /  |
[O] - [*]
```

where the 'O' is the vortex and the *'s are the shockwaves. Each tile has its own position number: the vortex is ALWAYS Position 1, followed by the first shockwave being Position 2 (in this case, the northeast shockwave), and Position 3 is the east shockwave. When summoning aetherbeasts, you want to travel northeast to Position 2, then south to Position 3. Thus, type the following command: `ppath ne s w`. The pathing system will automatically figure out how to travel back-and-forth between Positions 2 and 3, with the final direction entered being how to get back to Position 1 from Position 3.

Movement
--------

Steering is as simple as entering `n`, `ne`, etc, just as you normally do when walking. Gliding is that same directional command, just repeated. So to glide north you would enter `nn`, northeast would be `nene`, etc. 

If you ever manually steer the ship, autopilot will automatically be disabled. This is helpful should you ever need to escape from an enemy ship or aetherbeat.

Clarity
-------

`pc` to call out for a Clarity, `pce` to call out for an Emergency Clarity.

What's the difference? Functionally, nothing. A clarity's a clarity! But how it's placed in the Empath's queue is an entirely different story. An Emergency Clarity should only be for that: an emergency. If you're stuck and have to get away, etc. Otherwise, a regular clarity will do just fine!

Calling Targets
---------------

Sometimes you want to call out to your Combateers that there's a rogue aetherbeast flying around that needs to die. Easy! `ptar <target>`, and you'll announce on the ship's aether to target whichever beast you called out for.

Other Commands
--------------

All of the relevant commands can be found within the `Aliases` section of the scripting interface. There are too many to list here, so you'll have to figure the rest of them out for yourself!