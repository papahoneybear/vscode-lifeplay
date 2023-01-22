# Visual Studio Code - LifePlay Language Extension

- [Visual Studio Code - LifePlay Language Extension](#visual-studio-code---lifeplay-language-extension)
  - [Features](#features)
  - [Installation](#installation)
    - [Extensions Directory Location](#extensions-directory-location)
  - [Usage](#usage)
    - [Available Snippets](#available-snippets)
  - [Bug reporting](#bug-reporting)
  - [Contributing](#contributing)


This extension adds language LifePlay script highlighting to the Visual Studio
Code editor. It is actively in development and not feature-complete. The
extension is not published to VSCode's extension repository. See the
Installation section for details on how to manually install.

## Features

* Language support
* Constant recognition

## Installation

While in development, the extension can be installed and tested by either:

* Downloading the latest release and extracting it to your extensions directory.
* Cloning the repository to your extensions directory.

### Extensions Directory Location

Depending on your OS, you can find the extensions directory:

* Linux - ~/.vscode/extensions
* Windows - %USERPROFILE%\.vscode\extensions
* Mac - most likely ~/.vscode/extensions

## Usage

This extension currently provides basic code completion and snippets
(templates). To execute a snippet, type part of a keyword and select the
appropriate snippet in the contextual menu.

### Available Snippets

| Name                  | Keywords                      | Effect                              |
| --------------------- | ----------------------------- | ----------------------------------- |
| If block              | If, if                        | Creates if block                    |
| While block           | While, while                  | Creates while block                 |
| Random block          | Random, random                | Creates random block                |
| Dialog block          | Tag, tag                      | Creates a dialog block for 2 actors |
| Scene template        | WHAT, Scene                   | Creates scene file structure        |
| Stat template         | stat, STAT_ID                 | Creates stat file structure         |
| Action template       | ACTION_UNIQUEID, action       | Creates action file structure       |
| Interaction template  | ACTION_UNIQUEID, interaction  | Interaction file structure          |
| Module template       | module, MODULE_UNIQUEID       | Module file structure               |

## Bug reporting

Report any bugs or feature requests in GitHub.

## Contributing

If you would like to contribute to this project, please let me know.

