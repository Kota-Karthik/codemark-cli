# CodeMark CLI 🖥️📝🔍

CodeMark CLI is a command-line interface that helps you manage your coding assignments and tests with the CodeMark cloud service. With this tool, you can easily initialize the configuration, list assignments, fetch and check your code, submit your code for grading, and get AI-powered error recommendations. The tool is designed to simplify your experience with CodeMark and streamline your coding workflow. ⌨️💻👨‍💻

### Download
[<img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white"
     alt="Download from GitHub"
     height="60">](https://github.com/rootCircle/codemark-cli/releases)

## Installation instructions

To install and use CodeMark CLI, follow these steps:

1. Install the required dependencies by running the following command:

 `pip install pyrebase4 firebase_admin openai keyring appdirs tabulate fuzzywuzzy python-Levenshtein`

 Note: If you are a Windows user and encounter issues installing pyrebase, refer to this Stack Overflow post: https://stackoverflow.com/questions/53461316/pyrebase-install-on-windows-python-3-7-fails

2. Clone the CodeMark CLI repository by running the following command:
 `git clone https://github.com/rootCircle/codemark-cli.git`

3. Install CodeMark CLI by running the following command:

 `pip3 install --editable .`
 
 Note: If pip3 is not installed on your system, use pip instead. If you encounter permission issues, add the `--user` flag at the end of the command.

4. Verify that CodeMark CLI is installed correctly by running the following command:

 `codemark --help`

 If you encounter any issues, feel free to raise a pull request.

## Usage

To use CodeMark CLI, run the following command:

 `codemark [OPTIONS] COMMAND [ARGS]...`
 
### Options

- `--help`: Show this message and exit.

### Commands

- `check`: Checks the code against selected test cases and report errors. 🔍🐞
- `doctor`: Fixes any known common issues for the app. 💊🩺
- `get`: Fetches assignments from cloud, based on assignment Code. 🌩️📥
- `init`: Initialize the configuration globally for CodeMark. 🚀🔧
- `list`: Lists all assignments. 📜👀
- `logout`: Logout the user. 🔒👋
- `review`: Let AI review your code and recommend error you might be doing. 🔍💡
- `submit`: Submit the code against selected test cases and report errors. 🚀📝

### Requirements

CodeMark CLI requires a working internet connection to interact with the CodeMark cloud service. Additionally, make sure you have Python installed on your system.

## License

CodeMark CLI is released under the Apache License. See LICENSE for details.

## Support

If you have any questions or issues with CodeMark CLI, please raise an issue request. We are here to help! 💬👋

## Logo
![CodeMark logo](https://raw.githubusercontent.com/rootCircle/codemark-cli/main/logo.png)

