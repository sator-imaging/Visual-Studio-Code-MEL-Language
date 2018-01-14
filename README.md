# MEL Language Extension for Visual Studio Code
This package was built using files from [textmate/mel.tmbundle](https://github.com/textmate/mel.tmbundle/).


## Installation
On Visual Studio Code, Open Command Palette (Ctrl+P) and Run:
```
ext install mel
```

### Revision History
- v0.1.2: command colorization support.


### Links
- Visual Studio Marketplace:  
https://marketplace.visualstudio.com/items/sator-imaging.mel





### memo for development
How to create and install .vsix file.
1. Install Node.js from https://nodejs.org/
2. Run `npm install -g vsce`
3. `vsce package` to create .vsix file.
    - `code --install-extension "path_to_extension.vsix"` to install .vsix file.
4. Upload .vsix file to [here](https://marketplace.visualstudio.com/manage/), or run `vsce publish` to publish package to visual studio marketplace directly.
