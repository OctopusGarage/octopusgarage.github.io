# mesh-talk

> Encrypted desktop messaging across local and connected networks.

## Metadata

- Category: Private Communication
- Language: Rust
- GitHub: https://github.com/OctopusGarage/mesh-talk
- Homepage: https://octopusgarage.github.io/mesh-talk/

## Summary

Mesh-Talk is an open-source encrypted messenger for macOS, Windows and Linux. People create local accounts without an email address, phone number or cloud identity provider. Reachable devices communicate directly; existing routed networks and configured post-office bridges can connect sites. It uses a Rust protocol core with a Tauri and React desktop app.

No vendor-operated messaging server is required. Optional peer-operated post offices are running nodes that can temporarily hold encrypted events for offline delivery, subject to connectivity, capacity and retention limits. They cannot read message plaintext but may observe routing metadata. Offline delivery is not guaranteed permanent storage.

## Authoritative Documentation

- [Product overview and limitations](https://octopusgarage.github.io/mesh-talk/help/about-mesh-talk.html)
- [Markdown overview](https://octopusgarage.github.io/mesh-talk/index.md)
- [User guide](https://octopusgarage.github.io/mesh-talk/help/index.html)
- [AI documentation index](https://octopusgarage.github.io/mesh-talk/llms.txt)
- [Published releases](https://github.com/OctopusGarage/mesh-talk/releases)

The project manual owns detailed product facts. Check its documentation source version against your installed app; source documentation is not proof of a published Stable release.

## Fits Into OctopusGarage

Mesh-Talk extends the OctopusGarage local-first principle into communication across networks people control, without a required central vendor service.

## Best For

- Encrypted communication on a reachable LAN, including isolated networks without internet access.
- Desktop messaging across existing routed networks or configured post-office bridges.
- Local accounts, linked devices and optional peer-operated offline custody.

## Related Projects

- [tmux-claude-bot](https://octopusgarage.github.io/projects/tmux-claude-bot.md) - shares the goal of keeping local work reachable without hiding the underlying system.
- [net-auto-switch](https://octopusgarage.github.io/projects/net-auto-switch.md) - supports reliable local and proxy network conditions.

## Keywords

P2P, encrypted desktop messaging, local accounts, LAN, routed networks, post offices, end-to-end encryption, Rust, Tauri, React.
