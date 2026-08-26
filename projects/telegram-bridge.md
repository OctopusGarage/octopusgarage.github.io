# telegram-bridge

> Bridge Telegram messages into tmux and stream pane output back to chat.

## Metadata

- Category: Agent Control
- Language: TypeScript
- GitHub: https://github.com/OctopusGarage/telegram-bridge
- Homepage: `Not published`

## Summary

telegram-bridge forwards Telegram messages into a tmux pane and streams pane output back to chat. It is intentionally narrow: one chat interface, one tmux bridge, and a small surface for remote command injection and monitoring.

## Fits Into OctopusGarage

telegram-bridge represents the smallest useful unit of agent control in OctopusGarage. It covers the direct chat-to-terminal path without the broader multi-project control surface of tmux-claude-bot.

## Best For

- Telegram-to-terminal command forwarding.
- Remote monitoring of tmux pane output.
- Small integrations around terminal-based agents.

## Related Projects

- [tmux-claude-bot](https://octopusgarage.github.io/projects/tmux-claude-bot.md) - the broader multi-interface agent-control system.
- [octopusgarage-skills](https://octopusgarage.github.io/projects/octopusgarage-skills.md) - reusable agent workflow instructions that can complement tmux-based control.

## Keywords

Telegram bot, tmux, TypeScript, command bridge, remote terminal, agent control.
