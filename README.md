# LegionCore

#### Table of Contents
* [Introduction](#introduction)
* [Requirements](#requirements)
* [Install](#install)
* [Data Files](#data-files)
* [Common Issues](#common-issues)
* [Reporting issues](#reporting-issues)
* [Submitting fixes](#submitting-fixes)
* [Thank you](#thank-you)

#### Introduction
LegionCore is a **MMORPG** framework for WOW Legion *(Build 26972)*. This core is based off of the UWOW core leak of 2020. Which was derived from an old version of [TrinityCore](https://github.com/TrinityCore/TrinityCore). LegionCore is completely opensource and is developed by the community. To submit a pull request please follow this template [here](submitting-fixes).

If you want you can join the community discord: [here](https://discord.gg/rft8Jv459p).

# Requirements
 
[Windows specific](https://www.trinitycore.info/en/install/requirements/windows)
  
[Linux specific](https://www.trinitycore.info/en/install/requirements/linux)

[Mac specific](https://www.trinitycore.info/en/install/requirements/macos)

# Install
Most of the install steps are the same as the TrinityCore ones [here](https://www.trinitycore.info/en/install/Core-Installation).

# Data Files
This core has been updated with tools to generate all required data files.

Run the tools in the following order, using client build 26972:

1. `mapextractor`
2. `vmap4extractor`
3. `vmap4assembler`
4. `mmaps_generator`

The generated folders `dbc`, `maps`, `vmaps`, `mmaps`, `cameras` and `gt` are all required.

# Common issues
TODO

# Reporting issues
Issues can be reported via the [Github issue tracker](https://github.com/The-Legion-Preservation-Project/LegionCore-7.3.5/issues).

Please take the time to review existing issues before submitting your own to
prevent duplicates.

In addition, thoroughly read through the [issue tracker guide](https://community.trinitycore.org/topic/37-the-trinitycore-issuetracker-and-you/) to ensure
your report contains the required information. Incorrect or poorly formed
reports are wasteful and are subject to deletion.

Note that the issue tracker guide is from TrinityCore, but it also applies for this core.

# Submitting fixes
C++ fixes are submitted as pull requests via Github. For more information on how to
properly submit a pull request, read the [how-to: maintain a remote fork](https://community.trinitycore.org/topic/9002-howto-maintain-a-remote-fork-for-pull-requests-tortoisegit/).
For SQL only fixes, open a ticket; if a bug report exists for the bug, post on an existing ticket.

### Thank you
- [TrinityCore Authors](https://github.com/TrinityCore/TrinityCore/blob/master/AUTHORS)
- [LegionCore Contributors](https://github.com/dufernst/LegionCore-7.3.5/graphs/contributors)

-[world](https://release-assets.githubusercontent.com/github-production-release-asset/858205681/0d60eb23-ebbd-4b4e-b247-940dcafc80a5?sp=r&sv=2018-11-09&sr=b&spr=https&se=2026-02-04T10%3A23%3A29Z&rscd=attachment%3B+filename%3DLegionCore_full_735.26972_2024_10_23.7z&rsct=application%2Foctet-stream&skoid=96c2d410-5711-43a1-aedd-ab1947aa7ab0&sktid=398a6654-997b-47e9-b12b-9515b896b4de&skt=2026-02-04T09%3A22%3A32Z&ske=2026-02-04T10%3A23%3A29Z&sks=b&skv=2018-11-09&sig=G1Skc4r0qe1%2FKSTJP9vaIAkoEiHqxrYV7mAADX6uj8E%3D&jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmVsZWFzZS1hc3NldHMuZ2l0aHVidXNlcmNvbnRlbnQuY29tIiwia2V5Ijoia2V5MSIsImV4cCI6MTc3MDE5ODc1MiwibmJmIjoxNzcwMTk2OTUyLCJwYXRoIjoicmVsZWFzZWFzc2V0cHJvZHVjdGlvbi5ibG9iLmNvcmUud2luZG93cy5uZXQifQ.wtbHIX0wD_9d8fmH2rzHnP1YJbdARi32-uvSJ2FKtGw&response-content-disposition=attachment%3B%20filename%3DLegionCore_full_735.26972_2024_10_23.7z&response-content-type=application%2Foctet-stream) 

> **License: GPL 2.0** read [COPYING](COPYING).
