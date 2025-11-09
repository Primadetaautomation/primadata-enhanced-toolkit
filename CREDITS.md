# Credits & Attribution

## Primary Source

This plugin packages and adapts features from:

### my-claude-code-setup
- **Repository**: [centminmod/my-claude-code-setup](https://github.com/centminmod/my-claude-code-setup)
- **Author**: George Liu ([@centminmod](https://github.com/centminmod))
- **License**: MIT
- **Original Copyright**: Copyright (c) 2024 George Liu

## Features Integrated

### From my-claude-code-setup

#### Memory Bank System
- CLAUDE-activeContext.md template
- CLAUDE-patterns.md template
- CLAUDE-decisions.md template
- CLAUDE-troubleshooting.md template
- Memory bank synchronizer agent concept

#### Agents
- `code-searcher.md` - Efficient codebase search with Chain of Draft mode
- `get-current-datetime.md` - Brisbane timezone utility
- `memory-bank-synchronizer.md` - Documentation sync agent
- `ux-design-expert.md` - UX/UI design guidance

#### Commands

##### Cost Management
- `/ccusage-daily` - Daily usage tracking and metrics

##### Security Suite
- `/secure-prompts` - Prompt injection analysis
- `/security-audit` - OWASP compliance checker
- `/check-best-practices` - Security validation
- Security test examples

##### Prompt Engineering
- `/apply-thinking-to` - Anthropic thinking patterns
- `/convert-to-todowrite-tasklist` - Task list optimization

##### Documentation
- `/create-release-note` - Release notes generator
- `/add-update-readme` - README automation
- `/cleanup-context` - Memory bank cleanup

##### Other Commands
- `/init` - Memory bank initialization
- `/refactor` - Code refactoring assistance
- `/update-memory-bank` - Memory sync command

#### Skills
- `claude-docs-consultant` - Claude documentation fetcher

## Modifications Made

1. **Packaging**: Bundled as a Claude Code plugin with proper `.claude-plugin/plugin.json`
2. **Organization**: Maintained original directory structure for commands
3. **Integration**: Combined all features into a single installable package
4. **Documentation**: Added comprehensive README and installation instructions
5. **Attribution**: Added proper credits throughout

## Original File Attributions

Each file maintains its original structure and functionality from my-claude-code-setup:

- All agents in `/agents/` directory
- All commands in `/commands/` directory with subdirectories:
  - `/commands/anthropic/`
  - `/commands/architecture/`
  - `/commands/ccusage/`
  - `/commands/cleanup/`
  - `/commands/documentation/`
  - `/commands/promptengineering/`
  - `/commands/refactor/`
  - `/commands/security/`
- All skills in `/skills/` directory

## Special Thanks

- **George Liu (centminmod)** for creating and maintaining my-claude-code-setup
- The Claude Code community for inspiration and feedback
- **Anthropic** for Claude and Claude Code

## License Compliance

This adaptation is distributed under the MIT License, maintaining compatibility with the original project's MIT License. All original copyright notices are preserved.

## Maintainer

**Current Maintainer**: Primadata Automation
- GitHub: [@Primadetaautomation](https://github.com/Primadetaautomation)
- Email: rick@primadetaautomation.com

## Contributing

When contributing to this project, please:
1. Maintain attribution to original sources
2. Respect the MIT License terms
3. Credit any new sources appropriately

## Citation

If you use this plugin in your work, please cite both:

```
Original: centminmod/my-claude-code-setup
Adaptation: Primadetaautomation/primadata-enhanced-toolkit
```

---

*This CREDITS file ensures proper attribution of all integrated work. If you notice any missing attribution, please open an issue.*