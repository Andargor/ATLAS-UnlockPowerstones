# Unlock Powerstones

This mod unlocks powerstones for all users on the server, according to an INI configuration. Without the INI configuration, the mod does nothing.

This mod was developed for a small private server with only 3 "PVE" islands. It allows us to pre-unlock all missing powerstones from our grid, for the Kraken.

** WARNING: CHANGES FROM THIS MOD CANNOT BE REVERSED **
Please test before putting on a live server!

The mod is stackable and does not modify any existing settings.

MOD ID: 1723577244

**INI SETTINGS**

The following example is what we use on our server. It must be aded to GameUserSettings.ini for every tile in the grid.

We have the following powerstone islands and one trench:

```
Cay_C_EE_PVE (PowerStoneIndex 2)
Mnt_Y_EU_PVE (PowerStoneIndex 4)
Mnt_R_CH_PVE (PowerStoneIndex 6)
Trench_B (PowerStoneIndex 0)
```

The following configuration allows us to unlock all of the missing powerstones (indices 0,1,3,5,7 and 8 for powerstones, and indices 1 though 8 for essences). The entries UnlockPowerStone entries refer to the "PowerStoneIndex" in the IslandInstanceCustomDatas1/IslandInstanceCustomDatas2 settings. The UnlockSecondaryStone entries refer to essences, normally found in trenches and are used to unlock the hard mode Kraken (**not tested yet**)

```
[UnlockPowerstones]
UnlockPowerStone0=True
UnlockPowerStone1=True
UnlockPowerStone3=True
UnlockPowerStone5=True
UnlockPowerStone7=True
UnlockPowerStone8=True
UnlockSecondaryStone1=True
UnlockSecondaryStone2=True
UnlockSecondaryStone3=True
UnlockSecondaryStone4=True
UnlockSecondaryStone5=True
UnlockSecondaryStone6=True
UnlockSecondaryStone7=True
UnlockSecondaryStone8=True
```



