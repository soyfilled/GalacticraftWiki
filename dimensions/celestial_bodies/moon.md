# Moon

The **Moon** is the first celestial body that you can reach by using a [Tier 1 Rocket](/entities/vehicles/tier_1_rocket.md). Its surface consists of grayish blocks and is quite flat and bombarded with craters. As you walk on the surface, footprints are left behind. [Meteors](/blocks/environment/fallen_meteor.md) may fall on the Moon.

The Moon's gravity is 18% of [The Overworld](./overworld.md)'s and affects players, mobs, arrows, and dropped items. The fall damage is also 18% of Overworld's; you need to fall more than 16m to start taking damage, unlike the 3m on the Overworld (`3m / 0.18 ≈ 16.67m`), and more than 127m for a fatal fall (`(20HP / 0.18) + 16.67m ≈ 127.78m`).

The moon is uninhabitable by Overworld creatures due to the lack of [Oxygen](/common/oxygen.md). On the other hand, alien forms of hostile mobs can spawn in the dark along with the presence of [Moon Villages](/structures/other/moon_village.md), an alien version of Overworld villages.

The Moon dimension number is -28.

|||
| --- | --- |
| **Type:** | Moon |
| **Orbits:** | [Overworld](./overworld.md) |
| **Day-night cycle duration:** | 2h 40min (8 Overworld days) |
| **Gravity:** | 18% |
| **Fuel Depletion:** | ? |
| **Meteor Frequency:** | 7.0 (?) |
| **Life Support:** | Habitable |
| **Oxygen:** | No |
| **Pressure:** | 5% |
| **Wind Level:** | 0% |
| **Temperature:** | 0 (Neutral) |
| **Precipitation:** | ? |
| **Solar Energy Boost:** | 40% |

## Prerequisites
The Moon can be reached with the use of a Tier 1 Rocket, which can be built using the [NASA Workbench](/machines/space_base/nasa_workbench.md). [Rockets](/common/rocket.md) of higher tiers can be used, but they are more expensive.

## Day-night cycle
> [!NOTE]
> Since May 2017, the Moon and other planets [no longer follow the moon phases seen on the Overworld](https://github.com/micdoodle8/Galacticraft/issues/2643#issuecomment-300605153).

The Moon's day-night cycle is 2h 40min long, equaling 8 Overworld days and it is linked to the Moon phases seen on the Overworld. The daytime on the moon lasts from a full moon to the next new moon (4 Overworld days, equaling 1h 20min) and, logically, the nighttime lasts from the new moon to the next full moon.

Since the 1st Overworld night is full moon, you can have a safer landing within the 1st 4 Overworld days, and then the next 4 Overworld days are more dangerous since hostile mobs will be able to spawn in the dark, and so on. If you miss the counting, the moon phases can tell you when it is daytime or nighttime on the moon.

During the nighttime, the environment light levels go very low, allowing hostile mobs to spawn on the surface.

## Sky
The Overworld seems to be always fixed high up in the sky and only the Sun moves as the time passes by, but this is not entirely true. In fact the Overworld does move not because of the time but if the player travels away from the Moon's equator line (z = 0).

The Overworld apparently moves northward if the player travels southward, and southward if the player travels northward. If the player travels to z = 11,500 or z = -7,000, the Overworld is seen at the horizon line. The Overworld and Sun are perfectly aligned at z = 2,250 and an eclipse will always occur at the noon time on the Moon but it will not get dark ([video](https://www.youtube.com/watch?v=NAmqd__yzbo)).

## Time and Conversions
For command blocks and OP/server admins:

* Lunar Sunrise = 1st Overworld day sunrise = `/time set 0000` = real time: 00h00min
* Lunar Noon = 3rd Overworld day sunrise = `/time set 48000` = real time: 00h40min
* Lunar Sunset = 5th Overworld day sunrise = `/time set 96000` = real time: 01h20min
* Lunar Midnight = 7th Overworld day sunrise = `/time set 144000` = real time: 02h00min
* Lunar Sunrise = 9th Overworld day sunrise = `/time set 192000` = real time: 02h40min

## Geological Features
### Surface
The surface of the moon is formed by craters and is covered by [Moon Turf](/blocks/natural/moon_turf.md). Underneath it there is [Moon Dirt](/blocks/natural/moon_dirt.md), and underneath that you will find [Moon Rock](/blocks/natural/moon_rock.md). In the lower levels caves with [Moon Copper Ore](/blocks/ores/moon_copper_ore.md), [Moon Tin Ore](/blocks/ores/moon_tin_ore.md) and [Cheese Ore](/blocks/ores/cheese_ore.md) will generate. The moon has no naturally occurring lava.

Sometimes you may also find [Fallen Meteors](/blocks/environment/fallen_meteor.md) on the surface of the moon.

You can also find man-made holes, which are the entrance to [Moon Dungeons](/structures/dungeons/moon_dungeon.md).
### Structures
The moon features two kinds of generated structures: [Moon Villages](/structures/other/moon_village.md) and the [Moon Dungeons](/structures/dungeons/moon_dungeon.md).

## Mobs
### Passive Mobs
The only passive entity that spawns natively and lives on the moon is the [Moon Villager](/entities/mobs/moon_villager.md). Unlike normal villagers, they cannot trade, and only walk around in their Moon Villages.

### Hostile Mobs
At night and under low light levels, [Evolved Creepers](/entities/mobs/evolved_creeper.md), [Evolved Skeletons](/entities/mobs/evolved_skeleton.md), [Evolved Zombies](/entities/mobs/evolved_zombie.md) and [Evolved Spiders](/entities/mobs/evolved_spider.md) will spawn.

### Bosses
The Moon's boss is the [Evolved Skeleton Boss](/entities/mobs/evolved_skeleton_boss.md), which is found in the [Moon Dungeons](/structures/dungeons/moon_dungeon.md).
