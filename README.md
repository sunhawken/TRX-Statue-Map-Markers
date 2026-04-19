# TRX - Statue Map Markers

A patch ESP for the **TRX Mods Merged** mod pack that adds map markers for all 23 exterior TRX statue locations in Skyrim. Each marker is visible on the world map and supports fast travel.

## Requirements

- Skyrim Special Edition (or VR)
- [TRX Mods Merged](https://www.nexusmods.com/skyrimspecialedition/mods/) — the statues must be installed

## What It Does

Adds **Landmark**-type map markers for every exterior TRX statue that exists in the Tamriel worldspace. Two statues that share a cell (ArcherMastery and ArcherMasteryF) each get their own marker, slightly offset.

| Marker Name | Notes |
|---|---|
| TRX - Statue Alpha | South of Whiterun |
| TRX - Statue ArcherMastery | Reach mountains |
| TRX - Statue ArcherMasteryF | Reach mountains |
| TRX - Statue CandiGirl | |
| TRX - Statue Kitty | |
| TRX - Statue MagicLessons | |
| TRX - Statue Malakath | |
| TRX - Statue Milk Girl | |
| TRX - Statue MilkStation | |
| TRX - Statue Peach Candygirl | |
| TRX - Statue TriumphOfTheBeast | |
| TRX - Statue TrixieBadGirl | |
| TRX - Statue TrixieIdealBalance | |
| TRX - Statue TrixieJoke | |
| TRX - Statue TrixieTankard | |
| TRX - Statue TrixieThrone | |
| TRX - Statue TrixieWalker | |
| TRX - Statue TrixieWitchFlight | |
| TRX - Statue Trophy | |
| TRX - Statue WildPassion | |
| TRX - Statue WolfQueen | |
| TRX Statue MagicMeditation | |
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
