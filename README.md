# SA:MP DETUtils | Wiki
![image](img/detutils.png)
- Addition to SA:MP Standard Scripting Library with new stuff, anti-cheat system and many more functions!

Hello scripter! Welcome to *SA:MP DEntisT's Utilities* (or **detutils** for short) "read me" file. So, now, you may ask - what's this? Well - in general, this addition to SA:MP Standard Scripting package contains libraries that have in-game visible effects and libraries that contain new scripting features. 
- Below, you can find information about each library.
- For better understanding of this, make sure you know Pawn and a_samp - read all the docs [here](https://team.sa-mp.com/wiki-archive.html)...

## Examples

- [View](d_example.md) one simple example of script made using **SA:MP-DET Utilities**.

## Warnings
1. Always include **DETUtils** last, after all includes.
2. You'll need to use latest Pawn Community compiler in order to compile everything successfully.
## Docs
Click on blue text to see all information about each feature.
### Installation
------------------------------------------
- Learn more about [installation](d_installation.md)...
### Libraries
------------------------------------------
- Learn more about d_samp [here](d_samp.md)...
------------------------------------------
- Learn more: [d_commands.inc](d_commands.md)
- Learn more: [d_properties.inc](d_properties.md)
- Learn more: [d_fmargs.inc](d_fmargs.md)
- Learn more: [d_visual.inc](d_visual.md)
- Learn more: [d_anticheat.inc](d_anticheat.md)
- Learn more: [d_colours.inc](d_colours.md)
### Extra bonus
------------------------------------------
- Read more here: [Extra stuff](d_extra.md)
## Tests
- I regularly make test scripts with all new features I added to the library to ensure everything is working as expected.

Check out test files here:

- [Go to tests...](https://github.com/DentisT-SAMP/samp-detutils/tree/master/tests)

## Limits

- Everything has its limits, so does DETUtils - view them [here](d_limits.md)...

## Beta testing

- Beta testing program is currently down since this project is far away from being done. Also, according to news - new **open.mp** is coming soon, so these libraries shall be updated regularly to keep up with the project.

## Test log

- Recently, I started test logging program in which I log every library issue I spotted during testing. You can check it [here](d_testlog.md)...

## More languages

- English isn't the only language on the planet though, that's why I started language contribution program. I started it by making another library's core include called **d_text.inc** in which are all strings located. Your job as a language contributor is to simply translate it!

Check the file [here...](DETUTILS/d_extra/d_text.inc)

## Troubleshooting

If you're facing problems like function failed to call, function is not valid, critical errors - make sure you enable automatic debugging.
- Automatic debugging literally sends debug messages whenever it needs to.
- With this feature you can easily track problems and report them on Discord or try to troubleshoot them yourself.

To enable advanced debugging feature, use:

```pawn
#define detutils_debug
```

To join Discord server, [click here...](https://discord.gg/samp)

**NOTE:** After you enabled advanced debugging, your console may be full with *DETUtils* debug messages - in that case, don't worry.

## Compile-time errors

- Make sure you have updated dependencies and updated Pawn Compiler.

- You can get latest version of SA:MP standard libraries [here](https://github.com/pawn-lang/samp-stdlib)...

- You can get latest version of Pawn Compiler for SA:MP [here](https://github.com/pawn-lang/compiler/releases)...

### Thanks

- Big thanks to *open.mp* community for helping me during library development.

## SA:MP DEntisT's Utilities

### Legal:

- Version: MPL 1.1
    
    The contents of this file are subject to the Mozilla Public License Version 
    1.1 the "License"; you may not use this file except in compliance with 
    the License. You may obtain a copy of the License at 
    http://www.mozilla.org/MPL/
    
    Software distributed under the License is distributed on an "AS IS" basis,
    WITHOUT WARRANTY OF ANY KIND, either express or implied. See the License
    for the specific language governing rights and limitations under the
    License.
    
    The Original Code is SA:MP | DETUtils.
    
    The Initial Developer of the original code is DEntisT 'Unity' Brace.
    Portions created by the Initial Developer are Copyright C 2021
    the Initial Developer. All Rights Reserved.

### Contributors:

- DEntisT

### Thanks:

- aezzakmi - help during development

### Very special thanks to:

- Thiadmer - PAWN, whose limits continue to amaze me!

- Kye/Kalcor - SA:MP

- SA:MP Team past, present and future - SA:MP

- open.mp team present and future - open.mp

### Optional plugins:

- Incognito - streamer
- Y_Less (y-less.com, github.com/y-less) - sscanf


