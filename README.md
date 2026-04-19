# TRX - Statue Map Markers

A patch ESP for the **TRX Mods Merged** mod pack that adds map markers for all 23 exterior TRX statue locations in Skyrim. Each marker is visible on the world map and supports fast travel.

## Requirements

- Skyrim Special Edition (or VR)
- [TRX Mods Merged](https://www.nexusmods.com/skyrimspecialedition/mods/) — the statues must be installed

## What It Does

Adds **Landmark**-type map markers for every exterior TRX statue that exists in the Tamriel worldspace. Two statues that share a cell (ArcherMastery and ArcherMasteryF) each get their own marker, slightly offset.

| Marker Name | Location |
|---|---|
| TRX - Statue Alpha | South of Whiterun |
| TRX - Statue ArcherMastery | Reach mountains |
| TRX - Statue ArcherMasteryF | Reach mountains (offset 200 units) |
| TRX - Statue CandiGirl | Near Whiterun |
| TRX - Statue Kitty | Falkreath hold |
| TRX - Statue MagicLessons | Near Skytemple Ruins |
| TRX - Statue Malakath | East of Whiterun |
| TRX - Statue Milk Girl | Falkreath hold |
| TRX - Statue MilkStation | East Reach |
| TRX - Statue Peach Candygirl | North shore |
| TRX - Statue TriumphOfTheBeast | Solitude area |
| TRX - Statue TrixieBadGirl | Eastmarch |
| TRX - Statue TrixieIdealBalance | Near Ivarstead |
| TRX - Statue TrixieJoke | The Reach |
| TRX - Statue TrixieTankard | Near Whiterun |
| TRX - Statue TrixieThrone | Near Ivarstead |
| TRX - Statue TrixieWalker | Dawnstar area |
| TRX - Statue TrixieWitchFlight | East plains |
| TRX - Statue Trophy | Pine forest |
| TRX - Statue WildPassion | Ivarstead |
| TRX - Statue WolfQueen | Near Dragon's Tail |
| TRX Statue MagicMeditation | Throat of the World area |
| TRX Statue Waitress | Solitude docks |

Statues excluded (interior or non-Tamriel worldspace): CumGirl (interior cell), HorseRider (SolitudeWorld).

## Installation

Drop `TRX - Statue Map Markers.esp` into your `Data/` folder and enable it. Load after TRX Mods Merged.

## Source

The `Source/` directory contains the [Spriggit](https://github.com/Noggog/Spriggit) YAML serialization of the ESP, suitable for diffing and modifying.

To rebuild the ESP from source:
```
spriggit deserialize --InputPath Source --OutputPath "TRX - Statue Map Markers.esp"
```
