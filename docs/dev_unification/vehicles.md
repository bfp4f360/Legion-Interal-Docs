---
id: vehicles
title: Vehicles development strategy
sidebar_label: Vehicles dev strategy
---


## Aircraft

These are the following features of aircraft: `Simulation Type`, `Role`, `Seats/Cargo`, `Top Speed`,`Armor`, `Weapon types`, `Def. abilities`, `Fuel`

### Simulation Type

The possible values for this are `Heli`,`VTOL`,`Fixed`,`STOL`. The first three
should be trival. The last one, STOL, is short take of and landing which
basically means it needs to move forward a bit before it can take of
vertically(or diagonally since it has forward velocity already). 

### Role

Role requires two things, role and an IRL example. For the example it should try
to be around ww2/cold war era since thats when star wars was made and most of
the comparisons can be made(lasers = guns, lack of homing AA missiles, direct
line of sight combat)

These are some examples of roles:
`Fighter`,`Fighter-Bomber/Attack-Bomber`,`Bomber`,`Interceptor`,`Transport`,`AWACS`.
Ofcourse more can exist if it makes sense to get the general idea of the craft
across.

### Seats/Cargo
The values are  
`p` - Pilot  
`co-p` - Co pilot  
`g` - Gunner

There are things like a weapon systems officer, but since for the for seeable
future theres only 1, they are pretty much doing the role of a copilot.

### Speed

Units are in Kmph. I top speed, make sure to note if its with or without a
script(mainly helis). I would reccomend not having too many aircrafts breaking
the sound barrier as then the value of having high speed kind of gets diminished.

### Armor

Values are 0-10, with 0 being very little armor and 10 being high amounts of
armor. The 3 main sources of damage will be small arms (infantry), heavy
arms(vehicles,static turrets, other aircraft lasers), and missiles(rockets, AA).
Generally a missile is stronger then a heavy arm,and a heavy arm is stronger
then a small arm. Keep in mind the situations a vehicle might be in. For example
transports should have good amounts of armor because people like hot inserts and
its not fun if everyone dies on an insertion, think of it as giving the pilots
some breathing room to make mistakes since these are the more vulnerable crafts.
Crafts like fighters can get away with having less armor cause they can use
their speed and maneuverability as a defensive mechanism.

### Weapon types

Weapon types are `Guns`,`Missile/rocket`,`Bombs(Guided,Unguided,Cluster)`.

`Guns` - Have mag size, rate of fire, accuracy, damage, explosive damage, explosive range, speed, penetration as variables  
`Missiles/Rocekts` - Have mag size, rate of fire, damage, explosive damage,
exploisve range, speed, penetration, maneuverability, fuse distance, resistance to counter measrues, can it be guided, is it IR locking, is it radar locking.  
`Bombs` - Can be guided or unguided, single or a cluster, if its a cluster how
many pellets, whats the ration of UXO if any, what are those pellets, and what
shape do they fall at and what distance do they spawn at. There is also parameters of damage, explosive damage, explosive range and penetration.

### Defensive Abilities

So theres flares/chaff (really the same thing in arma 3) and smoke. Key things
to note are the rate of fire of the abilties, the mag count, reload time and how
much it covers( really only applicable to smokes, as in does the smoke cover 360 around the craft or just the front for example).