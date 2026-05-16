# Gases & Liquefied Gases
Galacticraft involves dealing with several different gases. Careful handling of gases is important in Outer Space!

## Galacticraft 2
The only gas implemented in [Galacticraft 2](/meta/general/galacticraft_2.md) is [Oxygen](#oxygen) which can be collected, piped, and used in several different machines. It an essential part of the life support systems for a player in a Space environment.

## Galacticraft 3
[Galacticraft 3](/meta/general/galacticraft_3.md) adds several gases, some of which can also be converted into liquid form.

List of gases in Galacticraft 3:
* [Oxygen](#oxygen)
* [Hydrogen](#nitrogen)
* [Nitrogen](#hydrogen)
* [Methane](#methane)
* [Carbon Dioxide](#carbon-dioxide)

List of liquefied gases in Galacticraft 3:
* [Liquid Oxygen](#liquid-oxygen)
* [Liquid Nitrogen](#liquid-nitrogen)

Methane can also be liquefied, in which case it is known as [Fuel](/wiki/blocks/liquids/fuel.md).

### Trivia
* In Galacticraft 3, all the gases and liquefied gases are coded as Forge fluids with their scientifically correct density, viscosity and temperature (taken from NASA data). This data is not currently used in Galacticraft 3, but if there is another Forge mod which makes use of this detailed fluid data then it will be accurate.
* In real life, methane, ethane, and propane, or a blend of them, are often liquefied for ease of transportation and to make a fuel: Liquefied Natural Gas (or LNG).

## Oxygen
"Oxygen" in Galacticraft can mean either breathable **Oxygen**, or pure (industrially-made) oxygen.

A range of machines in Galacticraft handle breathable **Oxygen** so that players can breathe in a space environment. An [Oxygen Collector](/wiki/machines/oxygen_collector.md) collects oxygen, [Oxygen Pipes](/wiki/machines/oxygen/oxygen_pipe.md) pipe it to other machines, an [Oxygen Storage Module](/wiki/machines/oxygen/oxygen_storage_module.md) can be used to store it.

The oxygen can be used in:
* [Oxygen Compressor](/wiki/machines/oxygen_compressor.md) - used for filling player [oxygen tanks](/meta/common/oxygen_tank.md).
* [Oxygen Distributor](/wiki/machines/oxygen_bubble_distributor.md) - used for making a bubble of breathable air in an unsealed space.
* [Oxygen Sealer](/wiki/machines/oxygen_sealer.md) - used to fill a [Sealed Space]() with breathable air.

Oxygen cannot be transferred from the Oxygen Collector or Oxygen Storage Module to other mods - only Galacticraft can use this oxygen, and only Galacticraft's own oxygen pipes can transport it.

### Trivia
In the early US space program (Mercury, Gemini and Apollo missions), space suits supplied astronauts with pure oxygen for breathing. The oxygen was at low pressure, around 1/5 of atmospheric pressure, to match the *partial pressure* of oxygen in earth's standard atmosphere but without the other atmospheric gases like nitrogen. This meant the missions did not have to carry the extra weight of nitrogen tanks, but it was also dangerous, as pure oxygen increases the fire risk.

The Russian space program has always used a mixture of nitrogen and oxygen for breathing purposes.

### Galacticraft 3
[Galacticraft 3](/meta/general/galacticraft_3.md) introduces oxygen made by industrial processes. It can be made either by electrolysing water in the [Water Electrolyzer](/wiki/machines/water_electrolyzer.md), or simply by feeding air on the [Overworld](/wiki/dimensions/celestial_bodies/overworld.md) (or any other planet with oxygen as a major atmospheric component) into a liquefaction plant, the [Gas Liquefier](/wiki/machines/gas_liquefier.md).

Uses:
* Oxygen can be made into [Liquid Oxygen](#liquid-oxygen) in the Gas Liquefier
* Oxygen can be piped through [Oxygen Pipes](/wiki/machines/oxygen/oxygen_pipe.md) into the [Oxygen Storage Module](/wiki/machines/oxygen/oxygen_storage_module.md), [Oxygen Compressor](/wiki/machines/oxygen_compressor.md), [Oxygen Distributor](/wiki/machines/oxygen_bubble_distributor.md) or [Oxygen Sealer](/wiki/machines/oxygen_sealer.md) and used for breathing
* Oxygen from the Water Electrolyzer can be used by any other industrial mod which has a use for a Forge fluid named *oxygen*

## Liquid Oxygen
**Liquid Oxygen** is a cryogenic (extremely cold) liquid form of [Oxygen](#oxygen). It is a useful way of transporting Oxygen in a compact form. It can be transported in special [canisters](), or in fluid pipes from other mods. It is not intended that it can be transported in buckets!

If **Liquid Oxygen** is placed in a normal oxygen-using machine like an Oxygen Sealer or Oxygen Storage Module, the liquefied oxygen turns back into a gas. 1 bucket (1000 mB) of Liquid Oxygen can make 5,555 units of [breathable oxygen](#oxygen).

Using the [Liquid Oxygen Canister](), Liquid Oxygen can also be used to refill player [oxygen tanks](/meta/common/oxygen_tank.md) in an emergency.

### Trivia
* In real life, Liquid Oxygen is transported in special flasks used for handling super-cold liquids.
* At -183°C it will be a constantly boiling liquid, whenever exposed to normal room temperatures. It boils rapidly because, to the Liquid Oxygen, room temperature (25°C) is a very hot temperature, well above its boiling point. When it boils it becomes oxygen gas.
* Because it is pure oxygen, Liquid Oxygen is extremely dangerous used near to any sparks or naked flames: any flammable object will burn almost instantly in pure oxygen (especially if it is dunked in liquid oxygen!)
* In the aeronautics and space industries, **Liquid Oxygen** is often known as **LOX**

## Nitrogen
**Nitrogen** is the main component of the Overworld atmosphere, and also found on [Mars](/wiki/dimensions/celestial_bodies/mars.md). It has no special uses in Galacticraft, except that it can be liquefied into [Liquid Nitrogen](#liquid-nitrogen). It can be considered a by-product of the process of making [Liquid Oxygen](#liquid-oxygen).

## Liquid Nitrogen
**Liquid Nitrogen** is a cryogenic (extremely cold) liquid form of [Nitrogen](#nitrogen). It is a way of transporting Nitrogen in a compact form. It can only be transported in special [canisters]().

If a [Liquid Nitrogen Canister]() is used (by right-clicking) on certain blocks, some of it will spill out and can cause the blocks to freeze.

## Hydrogen
**Hydrogen** gas is one of two products made when water is electrolysed using the [Water Electrolyzer](/wiki/machines/water_electrolyzer.md).

It is used in the [Methane Synthesizer](/wiki/machines/methane_synthesizer.md).

It can be piped using using the [Hydrogen Pipe](/wiki/machines/oxygen/hydrogen_pipe.md) in Galacticraft, Forge fluid pipes in other mods, or using *Pressurized Tubes* from Mekanism mod.

## Methane
**Methane** is made from carbon and [hydrogen](#hydrogen). With further processing, it can form a useful [Fuel](/wiki/blocks/liquids/fuel.md). There is currently no liquid Methane in the game, or to put that another way: liquid Methane **is** [Fuel](/wiki/blocks/liquids/fuel.md) - think of it as LPG (liquified petroleum gas).

### Trivia
The very cold outer planets of the Solar System - for example Titan, a moon of Saturn - are known to have lakes of liquid Methane. Liquid Methane is not yet implemented in Galacticraft.

## Carbon Dioxide
**Carbon Dioxide** is the most abundant gas in the atmosphere of [Mars](/wiki/dimensions/celestial_bodies/mars.md).

It can be used as a source of carbon in the [Methane Synthesizer](/wiki/machines/methane_synthesizer.md) if fitted with an [Atmospheric Valve](/wiki/items/liquids_gases/atmospheric_valve.md).

### Trivia
* Unlike other gases, Carbon Dioxide cannot be liquefied. If cooled, it forms a solid which looks like ice or snow, known as dry ice.
* In real life, the cold polar regions of Mars are sometimes covered with Carbon Dioxide snow, causing them to look white like the polar regions of Earth. Mars can also have clouds formed of dry ice.

## Argon
**Argon** is a neutral gas, and one of the components of the atmosphere of [Mars](/wiki/dimensions/celestial_bodies/mars.md). It has no current uses in Galacticraft. It is best to discharge it into the atmosphere using an [Atmospheric Valve](/wiki/items/liquids_gases/atmospheric_valve.md). However, if other mods are installed, it may have uses. For example, if Immersive Engineering is installed, Argon can be used in the Chemical Thrower.