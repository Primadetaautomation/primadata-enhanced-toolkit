# 🚀 Primadata Enhanced Toolkit

[![Version](https://img.shields.io/badge/Version-1.0.0-blue)](https://github.com/Primadetaautomation/primadata-enhanced-toolkit)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Based on](https://img.shields.io/badge/Based%20on-my--claude--code--setup-orange)](https://github.com/centminmod/my-claude-code-setup)

All-in-one Claude Code plugin bundling the best features from my-claude-code-setup for enhanced productivity, security, and cost management.

## ✨ Features

### 📦 Memory Bank System
Persistent project context with structured documentation:
- **CLAUDE-activeContext.md** - Current session state and goals
- **CLAUDE-patterns.md** - Established code patterns and conventions
- **CLAUDE-decisions.md** - Architecture decisions and rationale
- **CLAUDE-troubleshooting.md** - Common issues and solutions
- **memory-bank-synchronizer** agent - Keeps docs in sync with code

### 💰 Cost Management
Track and optimize your Claude Code usage:
- `/ccusage-daily` - Daily usage metrics and cost breakdown
- Token consumption tracking
- Model cost calculations
- Budget alerts and limits
- Usage optimization recommendations

### 🔒 Security Tools
Enterprise-grade security features:
- `/secure-prompts` - Analyze prompts for injection vulnerabilities
- `/security-audit` - OWASP compliance checking
- `/check-best-practices` - Security best practices validation
- Security test examples and patterns

### 🧠 Prompt Engineering
Advanced prompt optimization tools:
- `/apply-thinking-to` - Apply Anthropic's extended thinking patterns
- `/convert-to-todowrite-tasklist` - Optimize task lists for Claude
- **Chain of Draft (CoD)** mode - Achieve 80% token reduction
- Advanced prompt templates and patterns

### 📝 Documentation Automation
Streamline your documentation workflow:
- `/create-release-note` - Automated release notes generation
- `/add-update-readme` - Smart README updates
- `/cleanup-context` - Memory bank pruning
- Documentation templates and patterns

### 🤖 Specialized Agents
Powerful agents for specific tasks:
- **code-searcher** - Efficient codebase search with CoD mode
- **get-current-datetime** - Timezone-aware timestamps (Brisbane/GMT+10)
- **ux-design-expert** - Comprehensive UX/UI guidance with Highcharts
- **memory-bank-synchronizer** - Keep documentation in sync

### 🎯 Additional Commands
- `/init` - Initialize memory bank for new projects
- `/refactor` - Code refactoring assistance
- `/update-memory-bank` - Sync memory bank with codebase

## 🚀 Installation

### Via Primadata Marketplace (Recommended)
```bash
# Add the marketplace
claude plugin marketplace add Primadetaautomation/primadata-marketplace

# Install the enhanced toolkit
claude plugin install primadata-enhanced-toolkit@primadata-marketplace
```

### Direct Installation
```bash
# Install directly from GitHub
claude plugin install https://github.com/Primadetaautomation/primadata-enhanced-toolkit.git
```

### Local Development
```bash
# Clone the repository
git clone https://github.com/Primadetaautomation/primadata-enhanced-toolkit.git
cd primadata-enhanced-toolkit

# Install locally for testing
claude plugin install file:.
```

## 📖 Usage

### Initialize Memory Bank
When starting a new project:
```bash
/init
```
This creates the CLAUDE-* files in your project root.

### Track Daily Usage
Monitor your Claude Code costs:
```bash
/ccusage-daily
```

### Security Audit
Check your code for security issues:
```bash
/security-audit
```

### Secure Your Prompts
Analyze prompts for injection risks:
```bash
/secure-prompts "Your prompt here"
```

### Generate Release Notes
Create professional release notes:
```bash
/create-release-note
```

### Using Agents
Agents are automatically available. Claude will use them when appropriate, or you can request them explicitly:

```
"Use the code-searcher agent to find all API endpoints"
"Use the ux-design-expert agent to review this dashboard"
```

## 📁 Project Structure

```
primadata-enhanced-toolkit/
├── .claude-plugin/
│   └── plugin.json          # Plugin configuration
├── agents/                  # Specialized agents
│   ├── code-searcher.md
│   ├── get-current-datetime.md
│   ├── memory-bank-synchronizer.md
│   └── ux-design-expert.md
├── commands/               # Slash commands
│   ├── anthropic/         # Prompt engineering commands
│   ├── architecture/      # Architecture commands
│   ├── ccusage/          # Cost tracking
│   ├── cleanup/          # Cleanup utilities
│   ├── documentation/    # Doc automation
│   ├── promptengineering/# Prompt tools
│   ├── refactor/         # Refactoring tools
│   └── security/         # Security tools
├── skills/                # Claude skills
│   └── claude-docs-consultant/
├── README.md
├── LICENSE
└── CREDITS.md
```

## 🔧 Configuration

### Memory Bank Files
After running `/init`, these files will be created in your project:
- `CLAUDE-activeContext.md` - Track current work
- `CLAUDE-patterns.md` - Document code patterns
- `CLAUDE-decisions.md` - Record architecture decisions
- `CLAUDE-troubleshooting.md` - Log solutions to problems

### Cost Tracking
Configure budget alerts by editing the generated config after first use of `/ccusage-daily`.

## 🤝 Contributing

Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

Remember to maintain attribution to the original my-claude-code-setup project.

## 📜 Credits

This plugin is based on the excellent work from:
- **[centminmod/my-claude-code-setup](https://github.com/centminmod/my-claude-code-setup)** by George Liu
- Original concepts and implementations are credited in individual files

## 📄 License

MIT License - see [LICENSE](LICENSE) for details.

Original work Copyright (c) 2024 George Liu
This adaptation Copyright (c) 2024 Primadata Automation

## 🔗 Links

- **Marketplace**: [Primadata Marketplace](https://github.com/Primadetaautomation/primadata-marketplace)
- **Original Project**: [my-claude-code-setup](https://github.com/centminmod/my-claude-code-setup)
- **Issues**: [Report Issues](https://github.com/Primadetaautomation/primadata-enhanced-toolkit/issues)
- **Contact**: rick@primadetaautomation.com

---

**Made with ❤️ by [Primadata Automation](https://github.com/Primadetaautomation)**
**Based on [my-claude-code-setup](https://github.com/centminmod/my-claude-code-setup) by [centminmod](https://github.com/centminmod)**