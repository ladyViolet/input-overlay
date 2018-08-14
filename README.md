This is the sourcecode for the OBS studio plugin

[Latest layout presets](https://github.com/univrsal/input-overlay/tree/master/presets)

### How to use
![tut](https://i.imgur.com/kJMwIMC.png)

Compiling:
Compiled against XInput9_1_0.lib instad of XInput.lib (Because the first one is avaiable
on Windows 7).
I compile the plugin with Visual Studio 2017 and static linking. If you need help with
setting up a development environment you might want to take a look at a tutorial I wrote
over at my [blog](https://universallp.wordpress.com/2017/08/17/obs-studio/).
To enable static linking in VS do the following:
```
Right-click the project "input-overlay" in VS > Properties > Configuration Properties
> C/C++ > Code Generation
Choose /MT for runtime library in the Release Configuration 
```