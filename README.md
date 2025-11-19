# EmpowerHer iOS Configuration

Configuration repository for the EmpowerHer iOS application containing backend service URLs and environment settings.

## Overview

This repository holds the configuration file used by the EmpowerHer iOS app to connect to various backend services.

## Configuration File

### `ios-config.json`

Contains the base URLs for all backend services:

| Service | Description |
|---------|-------------|
| `backendBaseURL` | Main backend API endpoint |
| `backendServerURL` | Main backend server root |
| `photoAnalyzerBaseURL` | Photo analysis service |
| `mealPlanBaseURL` | Meal planning service |
| `faithContentBaseURL` | Faith-based content service |

## Usage

The iOS app fetches this configuration to determine which backend services to connect to. Update the URLs in `ios-config.json` to point to the appropriate environment (development, testing, production).

## Structure

```
empowerher-ios-config/
├── README.md
└── ios-config.json
```
