# Moleculer Snippets
This extension provide readymade snippets to use while writing code for moleculer microservices framework. [Read More](https://moleculer.services)

## Installation
   Search for `Moleculer Snippets` in vscode extensions or just follow this link. [Click here](https://marketplace.visualstudio.com/items?itemName=pavittarx.moleculer-snippets)

## How to use
Each Moleculer Snippets start with `moleculer` keyword. To insert a snippet start typing `moleculer`. As you would start typing, you might start seeing suggestion for all the available snippets. If you just type `mol` these snippets might still be visible to you. 

* Try using `Alt+Space`, if you don't see snippet suggestions.
* If you are unable to view the snippets after installing the extension. Make sure you have Intellisense enabled in vscode.

[Note]: These snippets only work with Javascript for now, typescript support may be provided soon. 

## Features

* Generate Configuration File `moleculer.config.js` (Default, Clean & Minimal Versions)
* Services Snippets (Default, Clean & Minimal Versions)
* Insert Service Lifecycle hooks (For Minimal Version Services)
* Snippets for few Middleware functions. (Sample, Emit, Local Action, RemoteAction) 


## Known Issues
* Javascript Snippets are usable in typescript files, but no types have been added.
* There are more possible snippets. Please let me know, what snippets would you prefer?

## Contributions
Give me a PR with your additions. 

### How to contribute? 
   1. Clone this repo & open it in vscode
   > git clone https://github.com/pavittarx/moleculer-snippets.json

   2. Edit `snippets/snippets.json`. You can refactor it to multiple files, if you'd like to. 
   3. Add your own snippets, make sure to include moleculer in prefixes & description. 
   4. Test your snippets by pressing `F5`.
   5. Commit & Open a PR

## Release Notes

### 0.2.0
Initial Release
