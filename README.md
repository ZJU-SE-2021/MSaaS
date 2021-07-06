<img src="https://avatars.githubusercontent.com/u/82106068" alt="MSaaS" style="zoom:50%;" />

# Medical System as a Service

> MSaaS is Laoheshan’s most technologically intelligent medical system. It's our course project for Software Engineering, but wen definitely wants to do something interesting.

A cross-platform medical system supporting iOS, Android, Web, and PWA.

## Features & Highlights

- Basic CRUD System with B/S, C/S Architecture
- Cross-Platform Ability Powered by React Native
- Video Diagnose Using WebRTC
- GraphDB & Deep-Learning Based AI Doctor
- Customable Information Visualization Using D3, ECharts, Leaflet and visx
- Intelligent API Maintainance with OpenAPI
- Cloud Native DevOps Development with GitHub Actions, Docker Registry and WatchTower
- ...

## Pipeline Status

| Parts                                                  | CI                                                           | CD                                                           |
| ------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Client](https://github.com/ZJU-SE-2021/MSaaS-Client)  | [![Test](https://github.com/ZJU-SE-2021/MSaaS-Client/actions/workflows/run-test.yml/badge.svg)](https://github.com/ZJU-SE-2021/MSaaS-Client/actions/workflows/run-test.yml) | [![Deploy](https://github.com/ZJU-SE-2021/MSaaS-Client/actions/workflows/build-image.yml/badge.svg)](https://github.com/ZJU-SE-2021/MSaaS-Client/actions/workflows/build-image.yml) |
| [Web](https://github.com/ZJU-SE-2021/MSaaS-Frontend)   | [![Test](https://github.com/ZJU-SE-2021/MSaaS-Frontend/actions/workflows/run-test.yml/badge.svg)](https://github.com/ZJU-SE-2021/MSaaS-Frontend/actions/workflows/run-test.yml) | [![Deploy](https://github.com/ZJU-SE-2021/MSaaS-Frontend/actions/workflows/build-image.yml/badge.svg)](https://github.com/ZJU-SE-2021/MSaaS-Frontend/actions/workflows/build-image.yml) |
| [Server](https://github.com/ZJU-SE-2021/MSaaS-Backend) | [![CI](https://github.com/ZJU-SE-2021/MSaaS-Backend/actions/workflows/ci.yml/badge.svg)](https://github.com/ZJU-SE-2021/MSaaS-Backend/actions/workflows/ci.yml) | [![Deploy](https://github.com/ZJU-SE-2021/MSaaS-Backend/actions/workflows/cd.yml/badge.svg)](https://github.com/ZJU-SE-2021/MSaaS-Backend/actions/workflows/cd.yml) |

## Architecture

![microservices_architecture](README.assets/microservices_architecture.png)

### Client Side

- Built with React Native and React Native Paper
- OpenAPI Generated Network SDK
- WebRTC with Native Support
- Unit Test with Jest

### Web Side

- Built with Ant Design Pro
- OpenAPI Generated Network SDK and TypeScript Document
- i18n Support
- WebRTC with Browser Support
- Information Visualization

### Server Side

- Built with ASP.NET 5
- Openbox OpenAPI 3 Support
- PostgreSQL for Database
- Redis for Cache
- ~~ELK for Logging~~ (consumes too much memory)
- Intergration Test with xUnit.net
- Stress Test with K6

### API Design

All API docs and SDKs are generated automatically with OpenAPI.
