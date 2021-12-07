# karabiner_files
A small repository of karabiner files to make standard PC keyboards work as I expect them on mac os

Either modify the mac os settings or use Karabiner, not both

## Modify mac os settings 

System settings - modifier keys

set cmd to ctrl
set ctrl to cmd
set caps lock to escape

# How-to
configuration file for Karabiner on ~/.config/karabiner/karabiner.json

put additional complex modifications under `~/.config/karabiner/assets/complex_modifications`

- `complex_modifications_PrtSc_to_screenshot_clipboard.json`
- `complex_modifications_Shift_PrtSc_to_screenshot_file.json`
- `complex_mods_gaulomatic.json`
- `control_to_command.json`

it's easier to just copy-paste these files. 
Karabiner creates unreadable file names if you import.


## Resources
### Documentation
https://karabiner-elements.pqrs.org/docs/

### Github site
https://github.com/pqrs-org/Karabiner-Elements