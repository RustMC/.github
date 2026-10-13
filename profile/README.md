# RustMC

RustMC is an independently developed Minecraft-compatible server project written in Rust. We are building toward a vanilla-style multiplayer world, with compatibility and performance claims backed by tests and measurements.

**Status: pre-alpha.** The server currently supports bounded local discovery and an opt-in Java 26.3 Creative terrain preview. A real Java client has joined and rendered terrain, but the preview is unauthenticated and read-only: there is no persistent or shared gameplay world. Bedrock discovery has synthetic socket tests, but no real-client validation yet. Vanilla world-generation parity has not been established. **Do not use RustMC for production worlds.**

## Start here

- [Source, current capabilities, and local quick start](https://github.com/RustMC/RustMC)
- [Roadmap and milestone exit criteria](https://github.com/RustMC/RustMC/blob/main/ROADMAP.md)
- [Versioned compatibility status](https://github.com/RustMC/RustMC/blob/main/docs/COMPATIBILITY.md)
- [Architecture and design decisions](https://github.com/RustMC/RustMC/blob/main/docs/ARCHITECTURE.md)
- [Development and testing guide](https://github.com/RustMC/RustMC/blob/main/docs/DEVELOPMENT.md)

External contributions are currently paused while the maintainer establishes a private security-reporting route and contribution process. Read the [contribution guidance](https://github.com/RustMC/RustMC/blob/main/CONTRIBUTING.md) and [security policy](https://github.com/RustMC/RustMC/blob/main/SECURITY.md) before contacting the project. Do not post vulnerabilities or private world data in public issues.
