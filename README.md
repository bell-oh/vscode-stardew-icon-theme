# VSCode Stardew Icon Theme

An extended version of klyap's Stardew Valley themed product icon pack. Forked from [klyap/vscode-stardew-icon-theme](https://github.com/klyap/vscode-stardew-icon-theme).

### Changelog
**Version 0.0.9 (#4) (1/1/2022)**
- .ipynb, .env, .mongodb, .vsix, .gch, .cyl, .txt, .zip, .o
- prettier.config.cjs
- tailwind.config.cjs, tailwind.config.js, tailwind.config.ts

**Version 0.0.9 (#3) (12/22/2022)**
- added "schema.prisma"

**Version 0.0.9 (#2) (11/20/2022)**
- added tsx, jsx, changed js
- added django-html
- added .py

**Version 0.0.9 (11/13/2022)**
- added icon for .prisma and typescript
- modified icons for javascript and node.js

**Version 0.0.8 (10/01/2022)**
- added icons for .cpp, .h, unit_tests.h, and README files  

<img width="165" alt="Screen Shot 2020-08-31 at 8 26 01 PM" src="https://user-images.githubusercontent.com/7905522/91792254-f5063500-ebc9-11ea-9baa-560540a92613.png">

### Autumn mode:

<img width="209" alt="Screen Shot 2020-10-02 at 6 08 57 PM" src="https://user-images.githubusercontent.com/7905522/94979891-6e9b8680-04da-11eb-8bd6-5ff0a63ad09f.png">

### Winter mode:

<img width="233" alt="Screen Shot 2020-10-27 at 9 45 19 PM" src="https://user-images.githubusercontent.com/7905522/97392155-5121c880-189e-11eb-86de-7c1886be767e.png">


### Download at https://marketplace.visualstudio.com/items?itemName=klyap.vscode-stardew-icon-theme
<img width="739" alt="Screen Shot 2020-10-02 at 4 14 12 PM" src="https://user-images.githubusercontent.com/7905522/94976903-52dcb400-04cb-11eb-8d84-04c2094ea725.png">

## Development

This extension uses image files directly from the `icons` folder in `icons.json`.

Open this repo in VSCode and hit F5 to test it out.

You will need to run to develop:
```yarn install```
```yarn install -g vsce```

### To publish a new version to the VS Code Extension Marketplace
Update the version number in package.json and run:
```vsce publish```

### To package for sharing with others
Run this command to generate a VSIX file:
 ```vsce package```
To load this VSIX extension into your VS Code IDE, replacing the file name with the generated one:
```code --install-extension vscode-stardew-icon-theme-0.0.3.vsix```

## Resources

Icons from https://stardewvalleywiki.com/Stardew_Valley_Wiki


