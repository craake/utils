# Introduction

This Git repository contains a collection of personal workspace utilities designed to enhance productivity in your development environment. At the moment, the repository includes one utility that utilizes fuzzy find on predefined directories, allowing you to quickly open desired directories in a new session (WezTerm workspaces and tmux, as a fallback, are supported at the moment).

# Installation

To use the personal workspace utilities, follow these steps:

Clone the repository to your local machine:

```bash
git clone https://github.com/craake/utils.git
```

Ensure you have the necessary dependencies installed. The current requirements are the following:
- [fzf](https://github.com/junegunn/fzf)
- [tmux](https://github.com/tmux/tmux)

Add the utility to your shell configuration (e.g., .bashrc, .zshrc, or .profile) for easy access.

# Usage

## Swipe (Fuzzy Directory Finder, looking for a better name)

To customize the predefined directories, modify two environment variables:
- ```$WORKSPACE```
- ```$PERSONAL```

Basic Usage:

To use the swipe, simply invoke the utility with the desired command in your terminal:

```bash
./swipe
```

The utility will present you with a list of directories to choose from, based on your predefined settings. Type a few characters of the directory name to filter the list using fuzzy search. Once you've found the desired directory, press Enter, and a new terminal session will be opened with the selected directory.

# Contributions

We welcome contributions to the repository. If you have any ideas for additional personal workspace utilities or improvements to the existing one, feel free to submit a pull request. Together, we can make our development environments even more efficient!

# License

This repository is licensed under the MIT License. For more details, see the LICENSE file.

