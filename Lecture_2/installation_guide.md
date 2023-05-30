# Python Installation Guide

This document provides step-by-step instructions for downloading and installing Python, setting up the PATH environment
variable, and verifying the Python installation.

## Python Download and Installation

Follow these steps to download and install Python on your computer:

1. Visit the official Python website at [https://www.python.org/](https://www.python.org/).

2. Hover over the 'Downloads' tab, and then click on the version of Python that matches your operating system (Windows,
   macOS, or Linux/UNIX). As of the time of writing, the latest Python version is Python 3.x.

3. Once the installer is downloaded, open it to begin the installation process.

    - For Windows and macOS users:
        - Ensure that the checkbox at the bottom is checked where it says "Add Python 3.x to PATH" before proceeding
          with the installation. This will automatically set the PATH environment variable.
        - Click on "Install Now".

    - For Linux/UNIX users:
        - Python is pre-installed on most Linux distributions and macOS. However, you might need to upgrade it to the
          latest version. You can do this using your distribution's package manager (like apt or yum).

## Setting up the PATH Environment Variable

The PATH environment variable in an operating system is used to locate the executables. When you type a command in the
command line, the system uses the directories listed in your PATH to search for the corresponding file.

Here's how to set up the PATH environment variable:

- For Windows users:
    - Python installer has already setup the PATH variable during installation.

- For macOS and Linux users:
    1. Open your terminal.
    2. Type `nano ~/.bash_profile` for macOS or `nano ~/.bashrc` for Linux and press enter.
    3. Add `export PATH="/usr/local/bin/python:$PATH"` at the end of the file.
    4. Save the changes and exit `nano` (Ctrl+X, then Y, then Enter).
    5. Type `source ~/.bash_profile` for macOS or `source ~/.bashrc` for Linux to reload the bash profile.

## Verification of Python Installation

To verify that Python is installed correctly, follow these steps:

1. Open your command line or terminal.

2. Type `python --version` and press Enter.

    - You should see Python's version number. If you do, this means Python is installed correctly and is ready to use.
      If not, go back to the installation steps and ensure you followed each one correctly.

Congratulations! You have successfully installed Python on your machine. If you encounter any issues, please refer to
the FAQ.md document or reach out in the Udemy course forum. Happy coding!
