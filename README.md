[![GitHub Release](https://img.shields.io/github/release/snell-evan-itt/EG4-Inverter.svg?style=for-the-badge&color=blue)](https://github.com/snell-evan-itt/EG4-Inverter/releases)
[![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/snell-evan-itt/EG4-Inverter/total?style=for-the-badge)](https://github.com/snell-evan-itt/EG4-Inverter/releases/latest)
[![HACS Default](https://img.shields.io/badge/HACS-default-blue.svg?style=for-the-badge)](https://hacs.xyz) [![Community forum discussion](https://img.shields.io/badge/COMMUNITY-FORUM-success?style=for-the-badge&color=yellow)](https://community.home-assistant.io/t/custom-component-ecoflow-cloud-api-for-us-users/799962)

# Home Assistant EG4 Inverter Integration

![EG4 Monitor Banner](docs/images/eg4_banner.png)

This is a custom Home Assistant integration for monitoring EG4 inverter systems. It connects to the EG4 web portal to fetch real-time data about your solar system.

## Installation

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?category=integration&repository=EG4-Inverter&owner=snell-evan-itt)

- Click above to install as a custom repository via HACS
- Restart Home Assistant
- Once restart is done, use Add Integration -> EG4 Inverter.

## Features

- Retrieves status and production metrics from an EG4 Inverter.
- Allows you to expose the inverter’s data to Home Assistant sensors.
- Easy setup and configuration via UI.

<p align="center">
  <a href="docs/images/01.png" target="_blank">
    <img src="docs/images/01.png" alt="EG4 Inverter Integration Selection" height="300"/>
  </a>
  <a href="docs/images/02.png" target="_blank">
    <img src="docs/images/02.png" alt="EG4 Configuration" height="300"/>
  </a>
  <a href="docs/images/03.png" target="_blank">
    <img src="docs/images/03.png" alt="EG4 Added" height="300"/>
  </a>
  <a href="docs/images/04.png" target="_blank">
    <img src="docs/images/04.png" alt="EG4 Entities" height="300"/>
  </a>
  <a href="docs/images/05.png" target="_blank">
    <img src="docs/images/05.png" alt="EG4 Energy Dashboard" height="300"/>
  </a>
</p>

## Configuration

The integration requires your EG4 portal credentials:
- Username
- Password