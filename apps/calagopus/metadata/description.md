# Calagopus

A modern game server management panel built in Rust. Deploy, monitor, and manage Minecraft, Hytale, and other game servers with industry-leading performance.

Calagopus is a modern, open-source game server management panel built with Rust and React. It provides a fast, secure interface for deploying, monitoring, and maintaining game servers - built for everyone from solo homelabbers to large hosting operators.

It draws inspiration from Pterodactyl but is written from scratch in Rust, with a focus on performance, security, and extensibility. The panel includes a rich extension API and welcomes community contributions.

## Variants

Calagopus comes in three variants on Runtipi:

- **Calagopus**: just the panel. It has no game server node of its own, so you need to connect one or more separate Wings nodes (on this or another machine) to run game servers.
- **Calagopus (AIO)**: the panel plus an integrated Wings node, so you can create and run game servers on your server right away with nothing else to set up. This is the best choice for most people.
- **Calagopus (Heavy AIO)**: everything in AIO, plus the toolchain needed to compile backend extensions on the device. Applying extensions triggers a local Rust build that can take several minutes and significant CPU, memory, and disk, so only pick this if you need backend extensions.

You are viewing: **Calagopus**.

## Links

- Website: https://calagopus.com
- Source: https://github.com/calagopus/panel
- Support: https://discord.gg/uSM8tvTxBV
