# Omarchy Configurator

A standalone configuration script for setting up a fresh Arch Linux DHH Omarchy installation with optimized defaults and essential tools.

## Quick Install

Run the configurator directly from GitHub:

```bash
curl -fsSL https://raw.githubusercontent.com/sroberts/omarchy-configurator/master/configurator.sh | bash
```

Or download and run manually:

```bash
curl -O https://raw.githubusercontent.com/sroberts/omarchy-configurator/master/configurator.sh
chmod +x configurator.sh
./configurator.sh
```

## What This Script Configures

The Omarchy Configurator sets up a complete development environment on a fresh Arch Linux DHH Omarchy installation, including:

### System Configuration
- Updates system packages to latest versions
- Installs essential development tools and utilities
- Configures optimized system settings for development work

### Development Environment
- Sets up common development tools (git, vim, etc.)
- Installs programming language runtimes and package managers
- Configures shell environment with useful aliases and functions

### Security & Performance
- Applies security hardening configurations
- Optimizes system performance settings
- Sets up firewall and basic security measures

### User Experience
- Configures desktop environment preferences
- Sets up productivity tools and shortcuts
- Applies DHH-inspired development workflow optimizations

## Requirements

- Fresh Arch Linux DHH Omarchy installation
- Internet connection for package downloads
- Root/sudo access for system configuration

## Development

This script is designed to be completely standalone and self-contained. All functionality is included within the single `configurator.sh` file to ensure it can be downloaded and executed without dependencies.

For development guidelines, see [CLAUDE.md](CLAUDE.md).

## License

MIT License - feel free to modify and distribute as needed.