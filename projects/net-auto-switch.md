# net-auto-switch

> Keep macOS WiFi and Clash Verge proxy nodes healthy with measured network checks.

## Metadata

- Category: Local Automation
- Language: Python
- GitHub: https://github.com/OctopusGarage/net-auto-switch
- Homepage: `Not published`

## Summary

net-auto-switch is a macOS daemon that measures network quality and switches WiFi or Clash Verge proxy nodes when quality drops. It is built for long-running work where unstable connectivity can interrupt coding agents, downloads, and remote sessions.

## Fits Into OctopusGarage

net-auto-switch is the connectivity layer of OctopusGarage. It keeps the local machine usable for unattended or remote agent work by making network switching measured, visible, and reversible.

## Best For

- macOS users who rely on Clash Verge proxy nodes.
- Automatic network recovery during long coding sessions.
- Region-aware proxy selection with launchd-managed background service.

## Related Projects

- [git-auto-sync](https://octopusgarage.github.io/projects/git-auto-sync.md) - depends on stable network conditions for repository sync.
- [envsentinel](https://octopusgarage.github.io/projects/envsentinel.md) - audits local network and environment signals.

## Keywords

macOS, WiFi, Clash Verge, proxy, daemon, launchd, network automation, Python.
