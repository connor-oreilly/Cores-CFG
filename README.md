# .cores-cfg ![CI status](https://img.shields.io/badge/build-passing-brightgreen.svg)

My main annoyance with other configs was how you would have to remove a good portion of the config if you wanted to integrate it with your existing configs, or at the very least would have to spend half an hour getting everyone to work how it once did. No longer.

## Installation

### Supported Operating Systems
All Operating Systems will work with the config, however only Windows 7, 8, 8.1, and 10 are fully supported, tested and feature fledged. Support outside of these systems is limited to the config, and I am not responsible for any damages caused by the end user.

### How to Install

Note: If you wish to integrate this config with your existing `autoexec.cfg` , you can just rename the autoexec from this repository or through the main release and rename it to something along the lines of `gfx` or `graphics` , ensure you keep the .cfg file extension at the end.

If you wish to install it normally, you can just download the [main release](https://github.com/corei17/Cores-CFG/releases) from the releases page. To install the config follow the steps below:
1. Download the release.
2. Unzip the file, and extract the files to your TF2 installation, this can typically be found in (C:/Program Files (x86)/Steam/steamapps/common/Team Fortress 2/tf/cfg).
3. Now you get to choose what launch options you want to run. First of all, open the config with your preferred text editor (Notepad++ will do for this) and read through the launch options, or you can click here to see a list and explanation of what launch options do what. For now I have provided some standard ones for you:

```
-dxlevel 90 -w (monitor width: 1920) -h (monitor height: 1080) -sw -noborder -reuse -usetcp -primarysound -snoforceformat
```

3.1. If you want to use fullscreen, you can remove `-sw` and `-noborder` and replace them with `-fullscreen` .

3.2. Open the Steam client, right click on Team Fortress 2 > Properties > Set Launch Options > and paste the launch options from Step 3 in.

4. Launch TF2, then close it once it reaches the menu.

5. Remove the launch option `-dxlevel 90` as it is no longer needed, and slows down alt-tabbing.

## Optional CFG Modules

```python
badcpu.cfg
badgpu.cfg
mouse-tweaks.cfg
no-tutorial.cfg
```

## Optional Custom Files

```python
cores-nokillstreaksound.vpk
cores-nodominationsounds.vpk
cores-noannouncervoices.vpk
cores-noapplausesounds.vpk
```

## License
Core @ [MIT](https://choosealicense.com/licenses/mit/)
