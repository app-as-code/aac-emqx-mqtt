# Changelog

All notable changes to this deployment definition are documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

### Changed

- Image pinned to EMQX 5.8.8 (LTS line) instead of a 6.x pre-release.

## [0.0.1]

### Added

- Initial App-as-Code service definition for EMQX with MQTT on TCP, TLS, WebSocket and secure WebSocket.
- Web dashboard on port 18083.
- Declarative base configuration (listeners, authentication, authorization) and bootstrap users for the built-in database.
- README with configuration reference and project icon.
