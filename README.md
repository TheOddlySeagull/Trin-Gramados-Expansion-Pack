<div align="center">

# Trin Gramados Expansion Pack — Skins & Liveries

Additional skins for Trin vehicles and related content themed around the lore and server of The Legends Of Gramdatis - Gramados Era.

</div>

[![Discord](https://img.shields.io/badge/Discord-join-7289DA?logo=discord&logoColor=white)](https://discord.gg/ujQR3wf)
[![Build Status](https://github.com/TheOddlySeagull/Trin-Gramados-Expansion-Pack/actions/workflows/build.yml/badge.svg)](https://github.com/TheOddlySeagull/Trin-Gramados-Expansion-Pack/actions/workflows/build.yml)

## Overview

This pack extends various Trin vehicles with new skins and liveries, including Gramados Police and service variants.

## Download

- GitHub Actions artifacts: each CI run uploads JARs for 1.12.2 and 1.16.5.
- Releases: push a tag (e.g., `v1.7.0`) to trigger a release with attached JARs.

## Requirements

- Minecraft with Immersive Vehicles (MTS/IV)
- Trin Part Pack (recommended)

## Installation (Players)

1. Install Immersive Vehicles (MTS/IV).
2. Download the JAR for your MC version.
3. Place it into your `mods` folder.
4. Launch the game.

## Building (Developers)

Prereqs:
- JDK 8
- Git and Gradle wrapper (included)

Quick build:
- Windows: `gradlew.bat buildForge1122 && gradlew.bat buildForge1165`
- Linux/macOS: `./gradlew buildForge1122 && ./gradlew buildForge1165`

Artifacts appear under `out/`.

CI:
- GitHub Actions builds on push/PR, uploads artifacts, and publishes releases on tags.

## Changelog

See [CHANGELOG.md](./CHANGELOG.md) for version history.

## License & Credits

- Content and branding © TheOddlySeagull and contributors. All rights reserved unless otherwise stated.
- Immersive Vehicles by its respective authors.

## Community

- Discord: https://discord.gg/ujQR3wf
- Issues: Use this repo’s Issues for bugs and feature requests.
