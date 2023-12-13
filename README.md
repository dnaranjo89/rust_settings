# rust_settings
[how to use keybinds](https://wiki.facepunch.com/rust/Keybinds)

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

```
effects.maxgibs -1    # To remove leftovers after destroying buildings
input.autocrouch "True"
physics.steps 60
physics.minsteps 60

bind u "+attack;+attack2"
bind j "gc.collect"  # Run Garbage collector
```

+meta.if_true "grassshadow 1";+meta.if_false "grassshadow 0"
