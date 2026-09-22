# RalphWorks

> Run bounded Pi coding loops with saved progress, checks, and local, Docker, or GitHub Actions execution.

## Metadata

- Category: Agent Control
- Language: TypeScript
- GitHub: https://github.com/OctopusGarage/ralphworks
- Homepage: https://github.com/OctopusGarage/ralphworks/releases/latest

## Summary

RalphWorks runs coding tasks through fresh Pi sessions, carries progress between iterations, and checks each result against commands supplied by the operator. It stops on completion, a request for human input, or an iteration, time, or cost limit. Runs can work in the current checkout, a Docker sandbox, or GitHub Actions; remote runs return inspectable results and patches.

## Fits Into OctopusGarage

RalphWorks provides the task execution loop for agent-assisted repository work. Its GitHub workflows can turn labeled issues and PR feedback into checked changes for maintainer review, while keeping the run record and delivery steps visible.

## Best For

- Coding tasks with clear acceptance checks and a bounded execution budget.
- Repository work that needs inspectable progress and a handoff when human input is required.
- Issue and PR workflows that prepare changes for maintainer review.

## Related Projects

- [tmux-claude-bot](https://octopusgarage.github.io/projects/tmux-claude-bot.md) - keeps interactive terminal agent sessions reachable from chat and local controls.
- [octopusgarage-skills](https://octopusgarage.github.io/projects/octopusgarage-skills.md) - provides reusable agent instructions that can be used in repository workflows.
- [git-auto-sync](https://octopusgarage.github.io/projects/git-auto-sync.md) - maintains local repository synchronization after changes are made.

## Keywords

Ralph loop, Pi coding agent, coding automation, GitHub Actions, issue workflow, pull request, Docker, checks, progress.
