# Voyage

**Open, encrypted, local-first tools for everyday work.**

Voyage is an open-source suite in early design. All Voyage apps share one foundation that works offline, syncs in real time, and leaves the keys to your data with you.

Learn more at [a.voyage](https://a.voyage/).

## Projects

### Voyage Projects

Project tracking that works online and offline. Voyage Projects will be the first app built on Voyage Sync.

### Voyage Sync

An offline-first, end-to-end encrypted data layer with access control down to the field. Voyage Sync is the foundation for all Voyage apps.

- **Offline-first:** Every device keeps a full local copy and works without a connection.
- **Collaborative:** Changes merge in real time through CRDTs.
- **End-to-end encrypted:** Relays store and forward data they cannot read.
- **Granular access:** A single object can have fields encrypted for different audiences.
- **Transport-agnostic:** Sync runs through relays, directly between peers, or via file bundles.
- **Self-hostable:** You can run your own relay servers.

The core will be written in Rust. V1 will ship with TypeScript bindings.

## Status

Voyage is in the design phase. A rough architecture draft is described on [a.voyage](https://a.voyage/) and will be updated as the work progresses. There is no usable release yet.

## Get involved

- Follow the project for updates on design milestones, first releases and ways to contribute: [a.voyage](https://a.voyage/)
- Questions and feedback: [contact@team.voyage](mailto:contact@team.voyage)

## Licence

Voyage is licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0) unless a repository states otherwise.
