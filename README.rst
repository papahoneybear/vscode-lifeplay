###############################################################################
Visual Studio Code - LifePlay Language Extension
###############################################################################

This extension adds language LifePlay script highlighting to the Visual Studio
Code editor. It is actively in development and not feature-complete. The
extension is not published to VSCode's extension repository. See the
Installation_ section for details on how to manually install.

.. _Installation
*******************************************************************************
Installation
*******************************************************************************

Binary Installation
===============================================================================

1. Download the latest `vsix` file from the repository_.
2. Open the **Extensions** pane: `ctrl-shift-x`.
3. Click the *elipsis* button in the explorer and choose **Install from VSIX**.
4. Select the downloaded `vsix` file.

Bleeding Edge Installation: Windows (Advanced Users)
-------------------------------------------------------------------------------

*Prerequisites*: git_, vscode_ 

1. Open a command prompt (`[Windows Key]` and type `cmd`).
2. Type `cd %USERPROFILE%\.vscode\extensions` and press **Enter**.
3. Type `git clone git@github.com:papahoneybear/vscode-lifeplay.git`.

Occasionally (or on a schedule with a batch script) run the following commands:

::
    cd %USERPROFILE\.vscode\extensions\vscode-lifeplay
    git pull origin main

Bleeding Edge Installation: Linux/Unix (Advanced Users)
-------------------------------------------------------------------------------

*Prerequisites*: git_, vscode_

1. Open a terminal window.
2. Type `cd ~/.vscode/extensions` and press **Enter/Return**.
3. Type `git clone git@github.com:papahoneybear/vscode-lifeplay.git`.

Occasionally (or on a schedule with a crontab entry) run the following commands:

::
    cd ~/.vscode/extensions/vscode-lifeplay
    git pull origin main

.. _usage
*******************************************************************************
Usage
*******************************************************************************

This extension currently provides basic code completion and snippets
(templates). To execute a snippet, type part of a keyword and select the
appropriate snippet in the contextual menu. Use the `tab` key to traverse the
templated areas.

Available Snippets
===============================================================================

If block
    **Keywords**: If|if
    
    Creates a basic *If* structure. Alternate templates are provided for 
    `If...Else` and `If...Elseif...Else`.

While block
    **Keywords**: While|while
    
    Creates a properly formatted *While* structure.

Random block
    **Keywords**: Random|random
    
    Creates a properly formatted *Random* structure.

Dialog block
    **Keywords**: Tag|tag
    
    Creates a dialog block for 2 actors.

Scene template
    **Keywords**: WHAT|Scene
    
    Creates scene file structure.

Stat template
    **Keywords**: stat|STAT_ID
    
    Creates stat file structure.

Action template
    **Keywords**: ACTION_UNIQUEID|action

    Creates action file structure.

Interaction template
    **Keywords**: ACTION_UNIQUEID|interaction

    Creates interaction file structure

Module template
    **Keywords**: module|MODULE_UNIQUEID

    Creates module file structure     

.. _feature:
*******************************************************************************
Feature Requests and Bug Reporting
*******************************************************************************
Request new features and report bugs in the Issues_ section.

.. include:: CHANGELOG.rst

.. include:: LICENSE.rst

.. _repository: https://github.com/papahoneybear/vscode-lifeplay/releases/latest
.. _Issues: https://github.com/papahoneybear/vscode-lifeplay/issues
.. _git: https://github.com/git-guides/install-git
.. _vscode: https://code.visualstudio.com/download