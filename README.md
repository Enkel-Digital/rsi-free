# rsi-free
Visual Studio Code extension "rsi-free" is a keymap extension with some key bindings that are meant to prevent RSI (Repetitive Strain Injuries)

## Features
- Maps all ***standalone*** use of \<Escape\> key to \<Alt + e\>
    - Meaning all default key bindings that use \<Escape\> can now be accessed with \<Alt + e\>
    - This DOES NOT include Combo type key bindings of \<Escape\> such as double \<Escape\> presses or \<Shift + Escape\>
    - Since we are unable to map a key binding to a modifier key such as \<Escape\>, the best way to then "replace" use of escape is to bind other keybindings like \<Alt + e\> to all the keybindings that are binded to \<Escape\> by default.

## Requirements
-- NIL --

## Extension Settings
This extension contributes the following settings:
* `rsi-free.enable`: enable/disable this extension

## Known Issues
- This issue is documented in the first feature, where only ***standalone*** use of \<Escape\> key's are mapped to \<Alt + e\>
    - Meaning no Combo type key bindings of \<Escape\> such as double \<Escape\> presses or \<Shift + Escape\>
    - Reason is because we are unable to map a key binding to a modifier key such as \<Escape\> through VS code extensions API, the best way to then "replace" use of escape is to bind other keybindings like \<Alt + e\> to all the keybindings that are binded to \<Escape\> by default.

## Roadmap
- [ ] Add more key bindings....

## Release Notes
### 0.0.1
Initial release with basic Escape key bindings.

---
## License, Author and Contributing
This project is developed and made available under the "MIT License". Feel free to use it however you like!  
If you have any questions, contact us via via at tech@enkeldigital.com  
Authors:
- [JJ](https://github.com/Jaimeloeuf)