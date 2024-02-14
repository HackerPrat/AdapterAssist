![Adapter Assist](https://github.com/HackerPrat/AdapterAssist/assets/38567597/e70e2499-5c15-40b3-8ebf-82525958c94a)
# Adapter Assist

Adapter Assist is a standalone executable made from a Python script designed to streamline the process of managing wireless adapter modes in Unix-like operating systems. It helps users easily switch between monitor mode and managed mode for their wireless adapters by providing convenient aliases that are also interactive.

## Installation

To use Adapter Assist, simply download the executable and run it in your terminal as follows:

```bash
wget https://github.com/HackerPrat/AdapterAssist/raw/main/AdapterAssist \
chmod +x AdapterAssist \
./AdapterAssist
```

Follow the on-screen instructions to choose your shell environment and add the necessary aliases to your shell configuration file.

## Usage

Once installed, Adapter Assist provides two main aliases:

- **monitor-assist**: Puts your wireless adapter(s) into monitor mode.
- **managed-assist**: Puts your wireless adapter(s) back from monitor mode into managed mode.

These aliases facilitate easy switching between modes, guiding you through the selection of the wireless adapter and providing a seamless experience.

## Compatibility

Adapter Assist is compatible with most Unix-like operating systems and supports the following shells:

- Bash
- Zsh
- Fish
- Ksh
- Csh
- Tcsh
- Dash
- Xonsh

**NOTE: It might be required for you to log out of your system and then log back in before the aliases work properly depending on your shell environment.**


## Contributing

If you encounter any issues or have suggestions for improvements, feel free to contribute by opening an issue or submitting a pull request on the [GitHub repository](https://github.com/HackerPrat/AdapterAsssist).

## License

This project is licensed under the MIT License.
