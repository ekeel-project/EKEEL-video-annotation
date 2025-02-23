# EKEEL Video Annotation System

The EKEEL Video Annotation System is a comprehensive tool designed for annotating educational videos. It allows users to add, edit, and manage annotations that can be used for various research and educational purposes. The system supports collaborative annotation, making it ideal for academic and research environments.

## Quickstart Guide

To streamline the process of cloning and configuring the EKEEL repository, it is highly suggested to use Visual Studio Code or PyCharm. The following guide is for Visual Studio Code.

### Prerequisites

- Ubuntu 22 or 24 (The project does not work on Windows due to library compatibility issues, but it works on Linux distributions or WSL).

### Step 1: Install VS Code

If you don't already have VS Code installed, download and install it from [here](https://code.visualstudio.com/).

### Step 2: Clone the Repository via VS Code

1. Clone the repo using the [official guide](https://code.visualstudio.com/docs/editor/versioncontrol).
2. Enter the repository URL: `https://github.com/ekeel-project/ekeel.git`.
3. Choose a local directory where you want to clone the repository.
4. VS Code will clone the repository and prompt you to open the cloned folder. Click **Open**.

### Step 3: Paste `secrets.env`

Ask the project manager for the `secrets.env` file and place the file in the directory `code/` (at the same level as `main.py`).

### Step 4: Download Miniconda Installer

```sh
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash Miniconda3-latest-Linux-x86_64.sh
```

#### Installation Prompts

- Press Enter to view the license.
- Type `yes` to accept the license.
- Press Enter to confirm the installation location.
- Type `yes` to initialize Miniconda3.

#### Activate and Verify the Installation

```sh
source ~/.bashrc
conda --version
```

#### Clean Up Installer

```sh
rm Miniconda3-latest-Linux-x86_64.sh
```

**Note:** Restart your terminal or run `source ~/.bashrc` after installation.