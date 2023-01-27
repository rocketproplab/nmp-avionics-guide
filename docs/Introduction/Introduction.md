# Introduction

In the Rocket Propulsion Lab New Member Project, teams are tasked with designing, fabricating, and launching a simple amateur rocket. This rocket has a simple mission profile: go as high as (reasonably and safely) possible, and recover the vehicle safely after flight.

To measure the success in achieving the objectives of this mission profile, an NMP rocket will be equipped with a simple avionics package that can record flight data.

## What is Avionics, and a Brief History
Avionics is a _portmanteau_ of "aviation electronics." It is a blanket term for any electronics that assist in controlling or operating aircraft and spacecraft. Avionics takes the form of many subfields, including guidance, navigation, and control (GNC); radio communications; pilot awareness (sensors); and more.

The first avionics packages were electromechanical in nature. Gryoscopes were physical objects that were rotated to maintain a frame of reference, and electronic signals were analog. However, as aviation and space flight developed in parallel to the semiconductor revolution, innovations in computer hardware enabled more sophisticated digital avionics. These digital avionics, like the Apollo Flight Computer, set the stage for a variety of new mission profiles. 

Today, hobbyist rocket flight computers start at about 8 times more powerful than the Apollo flight computer while having ~=4500x less mass. Innovations in computing continue to pay dividends, with advancements in artificial intelligence setting the stage for [entirely autonomous drone flights on distant worlds](https://www.nasa.gov/press-release/nasas-dragonfly-will-fly-around-titan-looking-for-origins-signs-of-life).

## Baseline Avionics Requirements
Your rocket's avionics package must perform the following functions:
- Record the maximum flight altitude.
- Save the maximum flight altitude to a storage medium so it can be read post-flight.

## The Avionics Package Levels
To assist NMP teams of all skill levels, a couple guides have been prepared:
- [Level 0](../Level0/Level0.md) is targeted at teams that just want to acquire a pre-existing flight computer and not design anything on their own.
- [Level 1](../Level1/Level1.md) is oriented at teams that want to make a flight computer using an Arduino Nano and breakout boards.