---
layout: post
title: "Weather hazards every CPL student should be able to explain: TAF, thunderstorms, western disturbances, fog and icing"
description: >-
  Five Meteorology topics that matter both in the DGCA paper and in the cockpit:
  reading a TAF's change groups, the three stages of a thunderstorm, what a western
  disturbance does to north India, radiation fog, and the icing temperature bands.
date: 2026-11-25
---

Meteorology is the subject students most often try to pass by memorising answers.
It works for a while, and then the paper asks the same idea from a different angle
and the memorised answer is no help. The way through is to understand a handful of
mechanisms properly. Once you can picture what the air is doing, most questions answer
themselves, and you will need exactly the same picture years later when you are
planning a real flight into a north Indian winter morning.

Here are five topics I would make sure of before any Meteorology attempt. Each one
links to the full chapter notes if you want to go deeper.

## 1. Reading a TAF: the change groups

Decoding wind, visibility and cloud in a TAF is mostly practice. What trips people up
are the change groups, because each one means something different about *time*:

- **FM** — from this exact time a new forecast takes over completely. Everything
  before it is forgotten.
- **BECMG** — a permanent change that arrives gradually somewhere inside the window.
  The window is normally 2 hours and never more than 4. Only the elements written
  change; the rest carry on.
- **TEMPO** — temporary spells. Each lasts less than 1 hour, and all of them together
  cover less than half of the window. Afterwards the main forecast returns.
- **PROB30 / PROB40** — a 30% or 40% chance. There is never a PROB50 or higher; at that
  point it is simply forecast with BECMG or TEMPO.

The one-line version: **after BECMG the new weather stays; after TEMPO it goes away
again.** So if a question asks for the weather "at the end of the period", ignore the
TEMPOs and follow the BECMGs.

A real-looking example makes the point. Take a Delhi winter TAF issued at 0500 UTC
(1030 IST), valid for 30 hours:

```
TAF VIDP 140500Z 1406/1512 29008KT 4000 HZ NSC
  BECMG 1413/1415 VRB02KT 1500 BR
  BECMG 1418/1420 0200 FG VV001
  TEMPO 1500/1504 0050 FG
  BECMG 1505/1507 32006KT 3000 BR NSC=
```

The wind dies away in the afternoon, mist sets in, and by 2000 UTC there is fog at
200 m with the sky obscured. Between 0000 and 0400 UTC there are spells of dense fog
down to 50 m, and the fog only lifts by 0700 UTC. The pilot's reading: a CAT I approach
into Delhi through that night is not going to work, so plan the alternate and the fuel.
The TAF told you that at half past ten in the morning.

One trap with older material: it prints time groups without the day (BECMG 0204,
TX42/10Z). Current TAFs carry the day as well (BECMG 2302/2304, TX42/2210Z). The
reading is the same; just remember the day is missing in the old form.

Full chapter, with more decoded Indian examples:
[TAF, ARFOR and ROFOR notes](https://ghostaviator.com/cpl/meteorology/met-26/notes).

## 2. Thunderstorms: three stages, three different hazards

Learn the life cycle and what each stage does to an aircraft, and you have most of the
thunderstorm chapter.

**Cumulus (building) stage.** A trigger lifts a parcel of air; it cools, condenses
into cumulus, and the latent heat released keeps it warmer than its surroundings, so
it keeps rising. The whole cell is updraught. Updraughts of 30 m/s, about 60 kt, are
not unusual. The hazards here are turbulence and icing.

**Mature stage.** The rising air reaches the tropopause, which acts as a lid, and
spreads sideways as the anvil. Precipitation falls and drags air down with it: the
downdraught is born, and now updraughts and downdraughts run side by side. When the
cold downdraught hits the ground it spreads out as the squall, and its leading edge is
the gust front. Lightning, heavy turbulence, sometimes hail. Each cell's mature stage
lasts about 20 to 40 minutes, but new cells keep forming, so the storm can go on far
longer. This is the most violent and most dangerous stage for aircraft.

**Dissipating stage.** Only downdraughts remain, precipitation decreases and the
cloud dies away.

Two things to remember the mature stage by: precipitation reaching the ground, and
up- and downdraughts side by side. And if there is enough vertical wind shear, the
downdraught separates from the updraught and the storm can become a self-sustaining
supercell that lasts for hours.

Downbursts and microbursts belong here too: local, violent downdraughts from a
thunderstorm. A downburst spreads damaging winds over more than 4 km. A dry microburst
comes from under a CB or its anvil, and a wet one from under a CB in heavy rain.

Full chapter: [Thunderstorm notes](https://ghostaviator.com/cpl/meteorology/met-13/notes).

## 3. Western disturbances: India's own frontal weather

India hardly ever sees a classic front, because the air masses over the plains are not
different enough. The exception is the north-west, which is reached by western
disturbances.

A western disturbance (WD) is a low or trough that travels from west to east across
India north of about 20°N. It comes from the Mediterranean, Caspian and Black Sea
region, carried east by the westerlies. It belongs to the mid-latitude depression
family, and by the time it reaches India it is already **occluded**, which gives a mix
of warm- and cold-front type cloud and weather. Over north-west India it strengthens
again, fed by Arabian Sea moisture and lifted by the mountains.

The numbers worth knowing: about 5 to 7 a month in winter, falling to none in the
monsoon, back again from October, moving at about 250 to 300 km a day. Most of the
cloud and rain or snow is always along the foothills. A WD with two or more closed
isobars at 2 hPa intervals is called a western depression.

What it does to your flying:

- **Coming in and passing:** low cloud, poor visibility, rain (snow on the hills),
  thunderstorms, hail, icing.
- **After it passes:** clear, calm nights and widespread radiation fog over the
  northern plains, often for several days, along with cold waves.

That second point is exactly why the next topic matters.

Full chapter: [Air masses, fronts and western disturbances notes](https://ghostaviator.com/cpl/meteorology/met-14/notes).

## 4. Radiation fog: the north Indian winter hazard

Every fog is the same thing: air cooled to its dew point at the surface. Radiation fog
forms on a clear night when the ground radiates its heat away and cools the air
touching it. The wind decides what you get:

- **Calm:** no mixing, so only a thin film of air cools and you get dew or frost, not fog.
- **Light wind, about 3–7 kt:** just enough turbulence to spread the cooling through a
  shallow layer: fog.
- **Stronger wind:** the cooling is mixed through too deep a layer, the surface does
  not get cold enough, and you get low stratus instead.

So the recipe is high relative humidity, a clear sky, a light wind of 3–7 kt and
stable air. It can form at relative humidity just under 100%, because hygroscopic
nuclei such as salt and pollution start condensation early.

The timing catches people out. The lowest temperature of the night comes just after
sunrise, so radiation fog is most likely to form or thicken around sunrise. Expect the
worst visibility just after dawn, not at midnight. It normally burns off 2 to 3 hours
after sunrise; a deep fog can last until about midday, and it usually lifts into low
stratus before it finally clears.

In India this is the December to February hazard, typically following a western
disturbance: the WD brings rain and moisture, the sky clears behind it, and the calm
nights that follow produce the fog. It is worst across north-west India, UP, Bihar,
Jharkhand, Chhattisgarh, Bengal and Assam.

One more practical point: the airfield can be plainly visible looking straight down
through a fog or haze layer, yet disappear on the approach, because you are then looking
forward and down along a long, slanting path through the same layer.

Full chapter: [Visibility and fog notes](https://ghostaviator.com/cpl/meteorology/met-7/notes).

## 5. Icing: remember five numbers

Airframe icing needs supercooled water: liquid water colder than 0°C. The warmer the
cloud, the more of its water is still liquid and the worse the icing. The colder it
gets, the more drops have already frozen into crystals, which bounce off instead of
sticking. For clouds other than cumulonimbus:

| Severity | Temperature range |
|---|---|
| Severe | 0°C to −7°C |
| Moderate | −7°C to −12°C |
| Light | −12°C to −20°C |
| Very light | −20°C to −40°C |

**Remember the cut points: 0, −7, −12, −20, −40.** A CB is the exception: its violent
updraughts carry large supercooled drops much higher, so it can give severe icing all
the way down to about −20°C.

Know the forms, too. Rime forms when small supercooled droplets freeze instantly and
trap air, so it is opaque, rough and light. Clear ice forms when large drops spread back
over the surface before freezing, so it is transparent, hard and heavy. **Clear ice is
the dangerous one.** In a cloud with a wide range of drop sizes you collect a mixture of
the two.

Two special cases appear often. Freezing rain under a warm front: rain from the warm
air above falls into a sub-zero layer below and arrives as large supercooled drops, so
flying beneath the front can load you with clear ice very fast, even out of cloud. And
carburettor icing, which needs no cloud at all: the air cools sharply in the venturi and
by fuel evaporation, and it can happen in clear, humid air at outside temperatures as
high as +30°C.

Full chapter: [Ice accretion notes](https://ghostaviator.com/cpl/meteorology/met-12/notes).

## How to use this

For each of these topics: read the chapter until you could explain it to someone else
without notes, then do the old questions, then go back over every one you got wrong and
find which part of the mechanism you had missed. That last step is where the marks are.

> **The short version: after BECMG the weather stays, after TEMPO it goes. A
> thunderstorm is dangerous when up- and downdraughts run side by side. A western
> disturbance reaches India occluded and leaves fog behind it. Radiation fog is worst
> just after sunrise. Icing cut points: 0, −7, −12, −20, −40, and clear ice is the
> dangerous one.**

*Capt. Pankaj Pahil is a pilot and DGCA flight & ground instructor. His free DGCA
CPL and ATPL notes, practice questions, video classes and a free demo class are at
[ghostaviator.com](https://ghostaviator.com).*
