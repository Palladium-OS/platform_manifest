![PalladiumOS](https://github.com/Palladium-OS/platform_manifest/blob/11/palladium.jpg)

---------------------------------------------------------------------------------------
Palladium OS
===========

To get started with Palladium-OS, you'll need to get familiar with [Repo](https://source.android.com/source/using-repo.html) and Version Control with [Git](https://source.android.com/source/version-control.html).


To initialize your local repository, run this command:
------------------------------------------------------

```bash
   repo init -u git@github.com:pd-temp/platform_manifest.git -b 11
```

Afterwards, sync the source by running this command:
----------------

```bash
repo sync -c -q --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```


Building Palladium OS
---------------
In order to build, use this command:
```bash
   . build/env*
   lunch palladium_<devicecodename>-userdebug
   mka palladium -j$(nproc --all)
```

---------------------------------------------------------------------------------------
 Credits:
 =======

 * [**LineageOS**](https://github.com/LineageOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**Project-Xtended**](https://github.com/Project-Xtended)
 * [**Project-Fluid**](https://github.com/Project-Fluid)
 * [**Project-Streak**](https://github.com/ProjectStreak)
 * [**ShapeShiftOS**](https://github.com/ShapeShiftOS)
 * [**Octavi-OS**](https://github.com/Octavi-OS)
 * [**Project-Awaken**](https://github.com/Project-Awaken)
 * [**DerpFest**](https://github.com/DerpLab)
 * [**BlissRoms**](https://github.com/BlissRoms)
 * [**Project-LegionOS**](https://github.com/Project-LegionOS)
 * [**AOSiP**](https://github.com/AOSiP)
 * [**POSP**](https://github.com/PotatoProject)
 * [**DotOS**](https://github.com/DotOS)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)