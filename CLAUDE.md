# Omarchy Configurator

This directory contains a shell script configurator for the Omarchy project.

## Project Structure

- `configurator.sh` - **Standalone configuration script** that configures a brand new Arch Linux DHH Omarchy install
- `README.md` - Project documentation

## Important Development Guidelines

**The configurator.sh file must be completely self-contained and standalone.** It should:
- Configure a fresh Arch Linux DHH Omarchy installation
- Be downloadable and executable without any dependencies on other files in this repository
- Include all necessary functions, variables, and logic within the single file
- Be ready to run immediately after download with just `./configurator.sh`

## Build Commands

Since this is a shell script project, there are no traditional build commands. To run the configurator:

```bash
./configurator.sh
```

## Testing

Test the configurator script in a fresh Arch Linux DHH Omarchy environment to ensure it works standalone.

## Linting

Use shellcheck for shell script linting:

```bash
shellcheck configurator.sh
```

## Notes

The configurator.sh file is the primary deliverable and must remain entirely self-contained for distribution and execution on target systems.