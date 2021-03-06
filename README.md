# Derby - Bourbon / Neat Autocompletion For Sublime Text

![derby-graphic](https://cloud.githubusercontent.com/assets/2628905/7764495/f21312f8-0017-11e5-8d8a-ec31f3f5f6b7.jpg)


[![Updated](https://img.shields.io/badge/project-v4.2.3-green.svg?style=flat)](https://packagecontrol.io/installation)

Sublime autocompletions to aid in using [Bourbon](http://bourbon.io/) and [Neat](http://neat.bourbon.io) in your projects. Named after the cocktail Derby which contains Lime and Bourbon. Special thanks to [@danieljacobarcher](https://github.com/danieljacobarcher) for contributing the latest updates.

## Installation Without Package Control

If you want to install this package without package control, follow these steps:

```
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages
git clone http://github.com/rossedman/derby Derby
```

You can also downlod the package [here](https://github.com/rossedman/derby/releases/latest) and place it in `~/Library/Application Support/Sublime Text 3/Installed Packages) if you do not want to follow the above instructions.

## How Do I Use Derby

To run an autocomplete, type in the property you are looking for and hit `Tab`.
	
	border-color --> @include border-color( red green null blue );
	helvetica --> font-family: $helvetica
	tint --> tint( red, 40% );
	
All properties can be referenced in the Bourbon and Neat documentation.

## Gotchas

Derby is set to work with SCSS and SASS in Sublime Text. I have personally not been able to get this to work with SCSS even though the source has been set in the auto completion files. You may have to switch your syntax to SASS to get this to work properly. 
