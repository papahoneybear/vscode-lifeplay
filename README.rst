===============================================================================
Visual Studio Code - LifePlay Language Extension
===============================================================================

This extension adds language LifePlay script highlighting to the Visual Studio
Code editor. It is actively in development and not feature-complete. The
extension is not published to VSCode's extension repository. See the
Installation_ section for details on how to manually install.

.. _Installation
Installation
-------------------------------------------------------------------------------

1. Download the latest vsix file from the repository_.
2. Open the **Extensions** pane: `ctrl-shift-x`.
3. Click the *elipsis* button in the explorer and choose **Install from VSIX**.
4. Select the downloaded vsix file.

.. _usage
Usage
-------------------------------------------------------------------------------

This extension currently provides basic code completion and snippets
(templates). To execute a snippet, type part of a keyword and select the
appropriate snippet in the contextual menu. Use the `tab` key to traverse the
templated areas.

Available Snippets
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

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
Feature Requests and Bug Reporting
-------------------------------------------------------------------------------
Request new features and report bugs in the Issues_ section.

.. include:: CHANGELOG.rst

License
-------------------------------------------------------------------------------

.. include:: LICENSE.rst

.. _repository: https://github.com/papahoneybear/vscode-lifeplay/releases/latest
.. _Issues: https://github.com/papahoneybear/vscode-lifeplay/issues