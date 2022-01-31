![PalladiumOS](https://github.com/Palladium-OS/platform_manifest/blob/12/palladium.jpg)

---

# Palladium OS

To get started with Palladium-OS, you'll need to get familiar with [Repo](https://source.android.com/source/using-repo.html) and Version Control with [Git](https://source.android.com/source/version-control.html).

## To initialize your local repository, run this command:

```bash
   repo init -u https://github.com/Palladium-OS/platform_manifest.git -b 12.1
```

## Afterwards, sync the source by running this command:

```bash
    repo sync --force-sync --no-tags --no-clone-bundle -j$(nproc --all)
```

## Building Palladium OS

In order to build, use this command:

```bash
   . build/env*
   lunch palladium_<devicecodename>-userdebug
   mka palladium -j$(nproc --all)
```

---

# Credits:

- [**LineageOS**](https://github.com/LineageOS)
- [**Project-Awaken**](https://github.com/Project-Awaken)
- [**Project-Fluid**](https://github.com/Project-Fluid)
- [**Project-Streak**](https://github.com/ProjectStreak)
