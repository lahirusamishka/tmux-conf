# Custom Tmux Configuration for macOS M1

This repository provides a custom Tmux configuration tailored for developers using macOS M1 environments. If you're new to macOS or Tmux, this configuration will help you set up an efficient terminal environment for your development tasks. It includes handy key bindings, plugins, and mouse support, making it a useful asset for developers looking for an optimized Tmux experience.

## Features

- **Custom Key Bindings**: Easily navigate between panes using `hjkl` keys, mimicking Vim-style navigation.
- **Mouse Support**: Seamlessly interact with Tmux panes and windows using your mouse.
- **Plugin Management**: Integrated with [Tmux Plugin Manager (TPM)](https://github.com/tmux-plugins/tpm) for easy plugin installation and management.
- **Theme**: Pre-configured with [Catppuccin Tmux Theme](https://github.com/catppuccin/tmux) for a visually appealing terminal experience.

## Setup

### Prerequisites

- macOS M1 or later
- Tmux installed on your machine
- Git installed

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/your-tmux-config.git ~/.tmux
   ```

2. Symlink the configuration file:

   ```bash
   ln -s ~/.tmux/tmux.conf ~/.tmux.conf
   ```

3. Install the Tmux Plugin Manager (TPM):

   ```bash
   git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
   ```

4. Start Tmux and install the plugins:

   - Launch Tmux: `tmux`
   - Press `Ctrl+s` followed by `I` (capital "I") to install all plugins.

### macOS M1 Configuration Notes

If you're using macOS M1 for the first time, make sure to install the appropriate ARM versions of your developer tools. For Tmux and other terminal tools, you can use [Homebrew](https://brew.sh/) to easily manage installations:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install tmux
```

## Customization

Feel free to customize this configuration to suit your workflow. Simply modify the `.tmux.conf` file to add or remove key bindings, plugins, and other settings.

## Contributing

If you have suggestions or improvements, feel free to submit a pull request or open an issue.

## License

This Tmux configuration is provided as a free asset for developers. You are welcome to use, modify, and distribute it as you see fit.

