<img width="1753" height="980" alt="image" src="https://github.com/user-attachments/assets/fcaa2a96-252f-49cf-897e-1bef42b13508" />

A collection of poses created by [Struggleville](https://discord.com/invite/m7P3F7Cwmu) and sponsored by Popcorn RP.

This includes all positions for traditional Sunni Salat and, in addition, some (not all) variants for different madhabs. Additional poses for Shia Salat are also included. 

<img width="1919" height="1079" alt="muslimprayer" src="https://github.com/user-attachments/assets/196a07cc-d02a-47c2-b3ed-c323871c7064" />

This pack also includes two Jewish prayer poses and six Christian prayer poses.


---

Need the dict and name for your emote system?

Below are all the included animations:

```
Islam:
	<Anim dict="smo@prayer_posepack_01" name="prayer_posepack_01_clip" />
	<Anim dict="smo@prayer_posepack_02" name="prayer_posepack_02_clip" />
	<Anim dict="smo@prayer_posepack_03" name="prayer_posepack_03_clip" />
	<Anim dict="smo@prayer_posepack_04" name="prayer_posepack_04_clip" />
	<Anim dict="smo@prayer_posepack_05" name="prayer_posepack_05_clip" />
	<Anim dict="smo@prayer_posepack_06" name="prayer_posepack_06_clip" />
	<Anim dict="smo@prayer_posepack_07" name="prayer_posepack_07_clip" />
	<Anim dict="smo@prayer_posepack_08" name="prayer_posepack_08_clip" />
	<Anim dict="smo@prayer_posepack_09" name="prayer_posepack_09_clip" />
	<Anim dict="smo@prayer_posepack_10" name="prayer_posepack_10_clip" />
	<Anim dict="smo@prayer_posepack_11" name="prayer_posepack_11_clip" />
	<Anim dict="smo@prayer_posepack_12" name="prayer_posepack_12_clip" />
	<Anim dict="smo@prayer_posepack_12" name="prayer_posepack_13_clip" />

Judaism:
	<Anim dict="smo@prayer_posepack_12" name="prayer_posepack_14_clip" />
	<Anim dict="smo@prayer_posepack_12" name="prayer_posepack_15_clip" />
	
Christianity:
	<Anim dict="smo@prayer_posepack_16" name="prayer_posepack_16_clip" />
	<Anim dict="smo@prayer_posepack_17" name="prayer_posepack_17_clip" />
	<Anim dict="smo@prayer_posepack_18" name="prayer_posepack_18_clip" />
	<Anim dict="smo@prayer_posepack_19" name="prayer_posepack_19_clip" />
	<Anim dict="smo@prayer_posepack_20" name="prayer_posepack_20_clip" />
	<Anim dict="smo@prayer_posepack_21" name="prayer_posepack_21_clip" />
```

## FOR RPEMOTES-REBORN USERS ON FIVEM: 

These are included in [rpemotes-reborn](https://github.com/alberttheprince/rpemotes-reborn) 2.0.2 by default, but we've provided them here in case you are using a custom version or another emote system. 

And add custom emotes to:

rpemotes-reborn\stream\[Custom Emotes]\Struggleville


If you are on an older version or your own custom version, add the below to your AnimationListCustom.lua:

```
["islampray1"] = { -- Made by Struggleville
    "smo@prayer_posepack_01",
    "prayer_posepack_01_clip",
    "Islam Pray - Qiyam Sadl",
    AnimationOptions = {
        onFootFlag = AnimFlag.LOOP,
    }
},

["islampray2"] = { -- Made by Struggleville
    "smo@prayer_posepack_02",
    "prayer_posepack_02_clip",
    "Islam Pray - Takbir",
    AnimationOptions = {
        onFootFlag = AnimFlag.LOOP,
    }
},

["islampray3"] = { -- Made by Struggleville
    "smo@prayer_posepack_03",
    "prayer_posepack_03_clip",
    "Islam Pray - Qiyam Qabd",
    AnimationOptions = {
        onFootFlag = AnimFlag.LOOP,
    }
},

["islampray4"] = { -- Made by Struggleville
    "smo@prayer_posepack_04",
    "prayer_posepack_04_clip",
    "Islam Pray - Ruku",
    AnimationOptions = {
        onFootFlag = AnimFlag.LOOP,
    }
},

["islampray5"] = { -- Made by Struggleville
    "smo@prayer_posepack_05",
    "prayer_posepack_05_clip",
    "Islam Pray - Sujud 1",
    AnimationOptions = {
        onFootFlag = AnimFlag.LOOP,
    }
},

["islampray6"] = { -- Made by Struggleville
    "smo@prayer_posepack_06",
    "prayer_posepack_06_clip",
    "Islam Pray - Julus",
    AnimationOptions = {
        onFootFlag = AnimFlag.LOOP,
    }
},

["islampray7"] = { -- Made by Struggleville
    "smo@prayer_posepack_07",
    "prayer_posepack_07_clip",
    "Islam Pray - Tasleem",
    AnimationOptions = {
        onFootFlag = AnimFlag.LOOP,
    }
},

["islampray8"] = { -- Made by Struggleville
    "smo@prayer_posepack_08",
    "prayer_posepack_08_clip",
    "Islam Pray - Tasleem 2",
    AnimationOptions = {
        onFootFlag = AnimFlag.LOOP,
    }
},

["islampray9"] = { -- Made by Struggleville
    "smo@prayer_posepack_09",
    "prayer_posepack_09_clip",
    "Islam Pray - tashahhud",
    AnimationOptions = {
        onFootFlag = AnimFlag.LOOP,
    }
},

["islampray10"] = { -- Made by Struggleville
    "smo@prayer_posepack_10",
    "prayer_posepack_10_clip",
    "Islam Pray - Tasleem 3",
    AnimationOptions = {
        onFootFlag = AnimFlag.LOOP,
    }
},

["islampray11"] = { -- Made by Struggleville
    "smo@prayer_posepack_11",
    "prayer_posepack_11_clip",
    "Islam Pray - Julus 2",
    AnimationOptions = {
        onFootFlag = AnimFlag.LOOP,
    }
},

["islampray12"] = { -- Made by Struggleville
    "smo@prayer_posepack_12",
    "prayer_posepack_12_clip",
    "Islam Pray - Julus 3",
    AnimationOptions = {
        onFootFlag = AnimFlag.LOOP,
    }
},

["islampray13"] = { -- Made by Struggleville
    "smo@prayer_posepack_13",
    "prayer_posepack_13_clip",
    "Islam Pray - Sujud 2",
    AnimationOptions = {
        onFootFlag = AnimFlag.LOOP,
    }

},

["jewishpray"] = { -- Made by Struggleville
    "smo@prayer_posepack_14",
    "prayer_posepack_14_clip",
    "Jewish Pray",
    AnimationOptions = {
        onFootFlag = AnimFlag.LOOP,
    }

},

["jewishpray2"] = { -- Made by Struggleville
    "smo@prayer_posepack_15",
    "prayer_posepack_15_clip",
    "Jewish Pray 2",
    AnimationOptions = {
        onFootFlag = AnimFlag.LOOP,
    }

},

["christianpray"] = { -- Made by Struggleville
    "smo@prayer_posepack_16",
    "prayer_posepack_16_clip",
    "Christian Pray",
    AnimationOptions = {
        onFootFlag = AnimFlag.LOOP,
    }

},

["christianpray2"] = { -- Made by Struggleville
    "smo@prayer_posepack_17",
    "prayer_posepack_17_clip",
    "Christian Pray 2",
    AnimationOptions = {
        onFootFlag = AnimFlag.LOOP,
    }

},

["christianpray3"] = { -- Made by Struggleville
    "smo@prayer_posepack_18",
    "prayer_posepack_18_clip",
    "Christian Pray 3",
    AnimationOptions = {
        onFootFlag = AnimFlag.LOOP,
    }

},

["christianpray4"] = { -- Made by Struggleville
    "smo@prayer_posepack_19",
    "prayer_posepack_19_clip",
    "Christian Pray 4",
    AnimationOptions = {
        onFootFlag = AnimFlag.LOOP,
    }

},

["christianpray5"] = { -- Made by Struggleville
    "smo@prayer_posepack_20",
    "prayer_posepack_20_clip",
    "Christian Pray 5",
    AnimationOptions = {
        onFootFlag = AnimFlag.LOOP,
    }

},

["christianpray6"] = { -- Made by Struggleville
    "smo@prayer_posepack_21",
    "prayer_posepack_21_clip",
    "Christian Pray 6",
    AnimationOptions = {
        onFootFlag = AnimFlag.LOOP,
    }

},

```





