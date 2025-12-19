Need the dict and name for your emote system?

Below are all thirteen:

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


FOR RPEMOTES-REBORN USERS ON FIVEM: 

Please note, for all versions of rpemotes 2.0.2 and above, these animations are included by default.

And add custom emotes to:

rpemotes-reborn\stream\[Custom Emotes]\Struggleville


If you are on an older version or your own custom version, add the below to your AnimationListCustom.lua:


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