# CoH Data Browser

A Windows program for exploring power and entity data from an installed version of **City of Heroes: Homecoming**.

CoH Data Browser provides a searchable interface for powers, enhancements, entities, and other game data directly from the files installed with CoH.

The UI and feature set is heavily inspired by City of Data, though this version has some additional features that CoD is missing (see below).

## Features

* **Power Search:** Browse and search powers, including detailed activation attributes, targeting information, effects, and enhancement compatibility.
* **Entity Search:** Examine NPCs, enemies, pets, and their associated powers.
* **Enhancement Data:** Browse enhancement sets and individual enhancements.
* **Power Effects:** Inspect damage, healing, buffs, debuffs, conditional effects, and other power attributes.
* **Level Scaling:** View how power attributes change at different levels and for different archetypes.
* **Branch Support:** Read data from installed Live, Beta, and Experimental game branches.
* **Power Comparison:** Compare powers across multiple installed game versions (e.g., live or beta) and easily see differences between them.
* **Raw Data:** Inspect decoded game data for additional details.
* **Local Operation:** No online service or account required.

## Known Issues

* The search feature is pretty slow when working with large data sets. This will be improved in future versions.
* Not all power information is shown since there are parts of the raw power data I still haven't figured out, but this tool displays enough for almost all users to find it helpful.

## Requirements

* Windows 10 or Windows 11 (probably runs on Linux/MacOS through Wine but have not tested these)
* City of Heroes: Homecoming installed locally

## Installation

1. Download the latest executable from the [Releases page](../../releases/latest)
2. Save the executable to a folder of your choice
3. Run the application
4. Select your Homecoming installation directory if prompted

## Updating Game Data

CoH Data Browser reads data from your locally installed game files instead of relying on a separately-maintained online database.

When Homecoming updates its game data, the application detects changes and refreshes its locally stored information.

## Notes

* This is an unofficial, community-developed application.
* This project is not affiliated with or endorsed by Homecoming Servers, LLC.
* Game data, names, and related intellectual property belong to their respective owners.
* This repository distributes compiled Windows executables only. Source code is not publicly available.

## Reporting Issues

If you encounter incorrect information, missing powers, application crashes, or other unexpected behavior, please open an issue using the **Issues** tab of this repository.

When reporting a problem, include the application version, game branch, steps to reproduce the issue, and any relevant screenshots.

Please do not include personal information in issue reports.
