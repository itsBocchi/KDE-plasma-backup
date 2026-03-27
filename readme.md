# KDE Plasma Setup (rice panels)

This repository contains configuration files for the KDE Plasma desktop environment, managed using `konsave`. It includes snapshots and visualizations of taskbar layouts for multi-monitor setups.

## Features

- **konsave Integration**: Easily save, export, import, and apply your KDE Plasma desktop configuration.
- **Multi-Monitor Taskbar Layouts**: Visual examples of horizontal and vertical taskbar configurations across two monitors.

## Getting Started

### Installation

Install `konsave` either via pip or the AUR:

- **pip**:
  ```sh
  pip install konsave
  ```

### Configuration Management with `konsave`

*   **Save Setup**: Create a snapshot of your current KDE Plasma configuration.
    ```sh
    konsave -s mylayout
    ```

*   **Export Setup**: Export your saved configuration to a `.knsv` file.
    ```sh
    konsave -e mylayout
    ```

*   **Import Setup**: Import a configuration from a `.knsv` file.
    ```sh
    konsave -i /path/to/mylayout.knsv
    ```
    Ensure you replace `/path/to/mylayout.knsv` with the actual path to your exported file.

*   **Apply Setup**: Apply a saved configuration.
    ```sh
    konsave -a mylayout
    ```

## Monitor Panel Layouts

Below are examples of taskbar configurations for a dual-monitor setup.

### Horizontal Layout (Right Monitor)

This image shows a horizontal taskbar arrangement, typically used on the primary or secondary monitor for a wider workspace.

![Horizontal Taskbar Layout](resources/Captura%20de%20pantalla_20260327_171629.png)

### Vertical Layout (Left Monitor)

This image demonstrates a vertical taskbar setup, often placed on the left or right edge for a different approach to screen real estate management.

![Vertical Taskbar Layout](resources/Captura%20de%20pantalla_20260327_171718.png)

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License.
