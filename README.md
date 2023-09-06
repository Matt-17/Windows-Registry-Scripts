# Windows-Registry-Scripts

A collection of Windows registry files (.reg) to tweak and optimize the Windows operating system.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [List of Registry Files](#list-of-registry-files)
- [Safety Precautions](#safety-precautions)
- [Contribution](#contribution)
- [License](#license)

## Introduction

This repository contains various `.reg` files that implement different tweaks for the Windows operating system. These tweaks range from optimizing the system's performance to customizing the user interface.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Matt-17/Windows-Registry-Scripts.git
   ```

2. Navigate to the directory:
   ```bash
   cd windows-registry-scripts
   ```

## Usage

1. Always backup your registry before applying any changes.
2. Double-click on the desired `.reg` file and confirm the prompt to merge changes into the registry.
3. Restart your computer for the changes to take effect.

## List of Registry Files

- `Elevated Network Drives.reg`: Allows elevated programs to recognize network drives mapped under a standard user.
- `Activate AdminShare.reg`: Allows networked access to shared folders, named pipes, and scheduled tasks for local accounts.
- `ContentIndexService Settings.reg`: Configures settings for the Content Index service used by Windows Search.
- `Remove Default Folders.reg`: Removes references to various default folders from the "My Computer" or "This PC" view.

## Safety Precautions

- Always backup your registry or critical data before applying any changes.
- It's recommended to test on a non-critical system or virtual machine first.

## Contribution

Contributions are welcome! Please open an issue if you encounter a bug or a pull request if you make a change.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
