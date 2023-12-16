# Rust custom settings
## Changes in Settings
Experimental
- Optimez loading: Partial   # To load all the game assets quicker

Graphics:
  - Max shadow lights: 0  # To let light go through buildings
  - Object quality: 0 # See through welding in oil rig

User interface:
  - Hide text while in ads: ON  # To move and fade out text near the crosshair

Options:
 - Head bob: Off # To remove the slight bumping when running
 - Show blood: Off # To remove the blood from the screen when in slow health


## Changes in the terminal
In the game, press F1 and then introduce the following commands
```
# To remove leftovers after destroying buildings
effects.maxgibs -1

# To ease small jump-ups from floor to floor
input.autocrouch true

# To jump higher
physics.steps 60
physics.minsteps 60
```

And then add a couple of keybinds (find the keybind documentation [here](https://wiki.facepunch.com/rust/Keybinds))
```
# To zoom in while aiming
bind mouse1 +attack2;+fov 90;fov 70

# Run Garbage collector
bind j "gc.collect"

# Show outgoing combatlog (i.e only the damage you´ve done)
bind f2 "consoletoggle;combatlog_outgoing"
```

