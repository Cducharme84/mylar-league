# CBL Tools Set up Tutorial

## Step 1: Install Python (Windows)

1. **Download Python Installer**:
    - Go to the official [Python website](https://www.python.org/).
    - Click on "Downloads" in the top menu.
    - Choose the latest version of Python for Windows.
    - The website will suggest the best version for your operating system. Click on the suggested download.

2. **Run the Installer**:
    - Once the installer is downloaded, double-click on it to run.
    - **Important**: Check the box that says "Add Python to PATH" at the bottom of the installer window.
    - Click "Install Now" to start the installation.
    - The installer will automatically set up Python on your system.

3. **Verify Installation**:
    - Open a command prompt (`cmd`) from the Start menu.
    - Type `python --version` or `python3 --version` and press Enter.
    - If Python is installed correctly, it will show the version number.

## Step 2: Clone a GitHub Repository

1. **Install Git**:
    - If you don't have Git installed, download it from the [official website](https://git-scm.com/downloads) and install it.

2. **Open a Command Prompt**:
    - Open a command prompt (`cmd`) from the Start menu.

3. **Navigate to the Directory**:
    - Use the `cd` command to navigate to the directory where you want to clone the repository. For example:
        ```shell
        cd C:\code\projects
        ```

4. **Clone the Repository**:
    - Use the `git clone` command followed by the URL of the GitHub repository you want to clone. For example:
        ```shell
        git clone https://github.com/flips22/mylar-league.git
        ```

## Step 3: Install Requirements from `requirements.txt`

1. **Navigate to the Repository**:
    - In the command prompt, navigate to the directory where the repository was cloned using the `cd` command.

2. **Install Requirements**:
    - The repository contains a `requirements.txt` file, use the following command to install the necessary packages:
        ```shell
        pip install -r requirements.txt
        ```
    - This command will read the `requirements.txt` file and install the necessary Python packages.

## Step 4: Configure config.ini
1. **Create custom config file:**
    - The script will read either a `config.ini` or `configPRIVATE.ini` You can edit either file, but I would suggest, you copy `config.ini` to a file call `configPRIVATE.ini` and then enter in all your information there.
2. **Edit the customer config file:**
    - Depending on which script you are using, will depend on how much of the config file you need to update
    - For CBL import (HTML version) you can fill out the mylar and comicvine sections. For CBL import (quick Version) you only need the mylar information.
    