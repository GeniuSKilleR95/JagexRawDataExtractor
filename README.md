# Jagex Data Extractor

Application that allows users to extract raw Jagex Account Data.

[![GitHub release](https://img.shields.io/github/v/release/GeniuSKilleR95/JagexRawDataExtractor?style=for-the-badge)](https://github.com/GeniuSKilleR95/JagexRawDataExtractor/releases)
[![Downloads](https://img.shields.io/github/downloads/GeniuSKilleR95/JagexRawDataExtractor/total?style=for-the-badge)](https://github.com/GeniuSKilleR95/JagexRawDataExtractor/releases)
[![Discord](https://img.shields.io/discord/123456789012345678?color=7289da&label=Discord&logo=discord&style=for-the-badge)](https://discord.gg/dentist)

## Features:

### Proxy Support:
- **SOCKS5 Proxy Configuration**: Optional proxy support with authentication
- **GUI Configuration**: User-friendly proxy setup dialog with validation

### Account Management:
- **Character Extraction**: Retrieves OSRS character data including account IDs and display names
- **Account Data Export**: Saves extracted data to JSON files
- **Multiple Account Support**: Handles accounts with multiple OSRS characters

### Data Storage:
- **JSON Export**: Saves authentication data to timestamped JSON files
- **Storage**: Stores data in `%APPDATA%/.tribot/Dentist/jagexDataExtractor/{displayName}/`

### User Experience:
- **Cross-Platform**: Works on Windows, macOS, and Linux

## Output Data:
The application extracts and saves the following account information:
- **Display Name**: Jagex account display name
- **Character ID**: OSRS character account ID
- **Game Session Token**: Authentication token for game access
