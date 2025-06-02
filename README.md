[![GitHub Release](https://img.shields.io/github/release/snell-evan-itt/EG4-Inverter.svg?style=for-the-badge&color=blue)](https://github.com/snell-evan-itt/EG4-Inverter/releases)
[![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/snell-evan-itt/EG4-Inverter/total?style=for-the-badge)](https://github.com/snell-evan-itt/EG4-Inverter/releases/latest)
[![HACS Default](https://img.shields.io/badge/HACS-default-blue.svg?style=for-the-badge)](https://hacs.xyz) [![Community forum discussion](https://img.shields.io/badge/COMMUNITY-FORUM-success?style=for-the-badge&color=yellow)](https://community.home-assistant.io/t/custom-component-ecoflow-cloud-api-for-us-users/799962)

# Home Assistant EG4 Monitor Integration

![EG4 Monitor Banner](docs/images/eg4_banner.png)

This is a custom Home Assistant integration for monitoring EG4 inverter systems. It connects to the EG4 web portal to fetch real-time data about your solar system.

## Installation

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?category=integration&repository=EG4-Inverter&owner=snell-evan-itt)

- Click above to install as a custom repository via HACS
- Restart Home Assistant
- Once restart is done, use Add Integration -> EG4 Inverter.

## Features

- Real-time monitoring of your EG4 inverter system
- Battery State of Charge monitoring
- Solar production monitoring
- Grid import/export monitoring
- Battery charge/discharge monitoring
- Customizable update intervals
- User-friendly sensor names and icons

## Configuration

The integration requires your EG4 portal credentials:
- Username
- Password

## Available Sensors

| Sensor | Unit | Description |
|--------|------|-------------|
| Battery State of Charge | % | Current battery charge level |
| Solar Production | W | Current solar panel power production |
| Grid Power | W | Current grid power flow |
| Battery Power | W | Current battery power flow |
| Daily Energy Production | kWh | Total solar energy produced today |
| Daily Grid Import/Export | kWh | Net grid energy exchange |
| Daily Battery Charge/Discharge | kWh | Net battery energy exchange |