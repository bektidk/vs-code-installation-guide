# Visual Studio Code Installation Guide

## Installation

### Step 1: Download

1. **Download**:
   - Visit the [Visual Studio Code download page](https://code.visualstudio.com/Download).
   - Choose the appropriate installer for your operating system:
     - **Windows**: Download the `.exe` file.
     - **macOS**: Download the `.dmg` file.
     - **Linux**: Download the `.deb` or `.rpm` file depending on your distribution.

### Step 2: Install

2. **Install**:

   - **Windows**:
     1. Run the downloaded `.exe` file.
     2. Follow the installation prompts:
        - Accept the agreement.
        - Choose the installation location.
        - Select additional tasks (optional).
        - Click `Install`.

   - **macOS**:
     1. Open the downloaded `.dmg` file.
     2. Drag the Visual Studio Code app to the Applications folder.

   - **Linux**:
     - **Debian/Ubuntu**:
       ```sh
       sudo dpkg -i <path-to-downloaded-file>.deb
       sudo apt-get install -f
       ```
     - **Fedora**:
       ```sh
       sudo rpm -i <path-to-downloaded-file>.rpm
       ```

### Step 3: Open Visual Studio Code

Launch Visual Studio Code from your Applications menu or using the terminal:
```sh
code
