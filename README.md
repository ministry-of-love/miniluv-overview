# miniluv-overview

Ministry of Love Unified Overview 2.0 (MiniLuvUO2)

## Description

This repository contains the Ministry of Love Unified Overview 2.0.  This was an effort by Logical Fallacy and Boneytooth Thompkins Isk-Chip to create a better overview that was updated for a more modern Eve.

We've begun by stripping out the overview and creating buckets that represent a type of overview.  They correspond as follows:

| #     | Bucket Description    |
| :---: | --------------------- |
| **0** | Gank / Kill           |
| **1** | Scouting              |
| **2** | Scooping and Loot     |
| **3** | FC Aid                |
| **4** | PvE                   |
| **5** | Nullsec/Lowsec Combat |
| **9** | Escape and Travel     |

The idea is to provide a holistic overview that addresses the needs of the line DPS, the support and the FC in the same
overview package.  The intent is that this single overview will allow players to transition and grow into roles without
many of the headaches that come with shifting from DPS to Support to FC.  Additionally, this provides us a standard base
from which the FC can request information that should be readily available.

## Installation

To install the MiniLuvUO2, clone the Github repository, or download the files from the website in the zip file format.
Extract the miniluv.yaml to the C:\Users\YOURUSERNAME\Documents\Eve\Overview folder.  If that folder does not exist, create that
folder.  In game, undock or pull up your overview options.  From there go to the Misc tab, and left-click import
overview.  Select MiniLuv from the list.


## Details

![alt tag](http://i.imgur.com/YbCddZu.png)

The overview provides 5 tabs, like any sensible overview.  The thought process behind these tabs is that the first tab
is travel tab, second tab is your Gank Kills tab, third tab is a friendly tab, for viewing friendlies on field,  The
fourth tab is the loot scooping tab for support members, while the last tab is for frogging out.

![alt tab](http://i.imgur.com/1kMEScn.png)

The overview is fairly compact compared to some Goon/CFC/Imperium overviews, sporting just 19 entries.  Below is a
description of each entity.


**0   freighters** This is a standard freighters overview, containing freighters, jump freighters and industrial command ships.

**0   miners** This is an inclusive miner ganking overview.  It includes expedition frigates, mining barges, exhumers,
industrials, blockade runners, deep space transports and industrial command ships.

**0   pods** This is a capsule only overview for shooting capsules.  The idea is you have this overview side by side of your
standard gank overview, and switch to it to kill the pod.

**0   thrasher ganking** This overview includes targets of interest for thrasher gankers.  That includes rookie ships,
shuttles, expedition frigates, covert ops frigates and capsules.

**1   scout cyno** This is a nullsec/lowsec cyno scouting overview.  It shows jump freighters, rorquals and rookie ships.

**1   scout freighters** Same as freighter overview above, but for scouting.

**1   scout indy** This is a scouting overview for industrial ganking, showing rookie ships, shuttles, industrials,
deep space transports and blockade runners.

**2   scooping** This overview is focused on people involved in the loot team during a gank.  It shows freighters and
jump freighters (so the DST can stay close to the freighter), deep space transports (so the freghters and looters can
stay close to the DST) and wrecks (so everyone can warp in and loot).  Special note, this overview show in-fleet DSTs,
Freighters, Jump Freighters, etc to allow for easy interaction via the overview.

**3   concord** This overview shows concord and only concord.  This is useful for FCs, bumpers, scouts to ascertain
the concord situation on a particular gank spot.

**3   fuckers: boosts** Overview for helping determine if the target has boosts.  Includes Battle Cruisers, Command
Destroyers and Command Ships.

**3   fuckers: jams** Overview for determine how many jams are on field.  Shows frigates, cruisers, force recons and
combat recons.  Does not show battleships capable of jams.

**3   fuckers: reps** Overview for determining how many repairers are on field.  Shows cruisers, logistics ships.

**4   null ratting** Standard ratting overview from Aryth pack.

**5   drones** Drones overview for nullsec and lowsec combat.

**5   fleet combat** General Fleet Combat overview.  Shows all ships that are not blue or in fleet.

**9   frogout highsec** Shows all warpable celestial **EXCEPT** planets.

**9   frogout nullsec** Shows all warpable celestials **EXCEPT** moons.

**9   travel** Shows non-friendly ships, stargates and stations for travelling.

**9   travel only** Same as above, but only stargets and stations.

## Contributing

If you wish to contribute:

1. Make a fork of the repository.
2. Load the MiniLuvUO2 into Eve.
3. Make your changes.
4. Export your changes to a new `miniluv.yaml` file.
5. Document your changes in a readme and make a pull request for the dev branch.
6. Talk to Logical Fallacy or Boneytooth Thomp2kins Isk-Chip for review.

## History

3/24/2016 - Added read me.
3/23/2016 - Initial creation and commit from original repository.

## Credits

Logical Fallacy for getting the ball rolling.
Boneytooth Thompkins Isk-Chip for updates.

## License

Fuck you
