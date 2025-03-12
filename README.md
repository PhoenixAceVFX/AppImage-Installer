# AppImage Installer

AppImage Installer is a Bash script designed to facilitate the global installation of AppImage files on Linux systems, enabling command aliasing for easier application execution. 

## Features

- **Global Installation**: Deploy AppImage applications system-wide, making them accessible to all users.
- **Command Aliasing**: Assign custom command aliases to AppImage applications for simplified execution.
- **Dependency Management**: Automatically checks for and installs necessary dependencies to ensure smooth operation.

## Prerequisites

- Ensure you have `git` installed to clone the repository.

## Installation Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/PhoenixAceVFX/AppImage-Installer.git
   ```


2. **Navigate to the Directory**:
   ```bash
   cd AppImage-Installer
   ```


3. **Create a 'Compiled' Directory**:
   ```bash
   mkdir Compiled
   ```


4. **Add Your AppImage Files**:
   Place your AppImage files into the newly created 'Compiled' directory.

5. **Configure the Installer**:
   - Open the `Installer.sh` script in your preferred text editor.
   - Locate line 115, where you can specify the AppImage files and their corresponding command aliases.

6. **Run the Installer**:
   ```bash
   bash Installer.sh
   ```


7. **Verify Installation**:
   Test the newly created command aliases to ensure the applications run as expected. The script will display the commands that should now be operational.

## License

This project is licensed under the GNU General Public License v2.0. For more details, refer to the [LICENSE](https://github.com/PhoenixAceVFX/AppImage-Installer/blob/main/LICENSE) file.

## Acknowledgments

AppImage Installer is utilized in the [HyprUpld](https://github.com/PhoenixAceVFX/HyprUpld) project to manage command aliasing for AppImage applications.

For any questions or contributions, please feel free to open an issue or submit a pull request on the [GitHub repository](https://github.com/PhoenixAceVFX/AppImage-Installer).

*Note: AppImage is a format for distributing portable software on Linux without requiring superuser permissions to install the application. citeturn0search19* 
