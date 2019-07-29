.. cssclass:: dynamic-content windows

Step1: Installing Gauge on Windows
==================================

This section gives specific instructions on setting up Gauge in a Microsoft Windows environment.

Install using Windows Installer
-------------------------------

Download the following installation bundle to get the latest stable release of Gauge.

.. cssclass:: extension-link

`windows Installer <https://github.com/getgauge/gauge/releases/download/v1.0.5/gauge-1.0.5-windows.x86_64.exe>`__

Once you finished installing Gauge, you can go ahead and `install the Gauge Extension for VS Code Plugin <#step-2-installing-gauge-extension-for-vscode>`__

Alternate Installation Methods
------------------------------

.. cssclass:: dynamic-content windows collapsible

Install using Chocolatey Package Manager
--------------------------

.. cssclass:: dynamic-content windows code-block

System Requirements
`Chocolatey Package Manager <https://chocolatey.org/>`__

.. cssclass:: dynamic-content windows

For this to work, you will need to install Chocolatey. If you have chocolatey installed then all you need to is to follow the steps below, it will download and install Gauge.

.. note:: Some of the following instructions mention the "command prompt". Where this is used, it refers to the Windows cmd.

.. cssclass:: dynamic-content windows

* To open your Command Prompt, click your Start Button
* In Search type, "cmd"
* Then click on "Command Prompt"
* Type the following command in your Command Prompt to install Gauge.

.. cssclass:: dynamic-content windows
.. code-block:: console

    choco install gauge

.. cssclass:: dynamic-content  windows collapsible

Install using Zip file
----------------------

.. cssclass:: dynamic-content windows content

Download the following zip installer.

.. cssclass:: dynamic-content windows content extension-link

`gauge-1.0.5-windows.x86_64.zip <https://github.com/getgauge/gauge/releases/download/v1.0.5/gauge-1.0.5-windows.x86_64.zip>`__

.. cssclass:: dynamic-content windows content

2. Extract it to a location and add it to system path using the following command in `Powershell <https://docs.microsoft.com/en-us/powershell/>`__.

.. cssclass:: dynamic-content windows content

.. code-block:: console

    PS>  Expand-Archive -Path gauge-1.0.5-windows.x86_64.zip -DestinationPath custom_path


.. cssclass:: dynamic-content  windows collapsible

Install using NPM installation
------------------------------

.. cssclass:: dynamic-content windows content text-block

System Requirements
Node.js
To install gauge using NPM you will need the latest node version.
* if you have Node.js already installed - to get the latest version use the following command:
`npm install -g npm@latest`.

.. cssclass:: dynamic-content windows content

You can install Gauge by running the following command in Powershell/Command Prompt.

.. cssclass:: dynamic-content windows content
.. code-block:: console

    npm install -g @getgauge/cli

.. cssclass:: dynamic-content  windows collapsible

Nightly Installation
--------------------

.. cssclass:: dynamic-content windows content

Nightly release are latest development snapshots of Gauge. They have the latest features being developed, but are unstable. Downnload the Gauge archive from here. Extract it to a location and add it to system path.

.. cssclass:: dynamic-content windows content
`gauge-1.0.6.nightly-2019-07-25-windows.x86.exe <https://bintray.com/gauge/Gauge/download_file?file_path=windows%2Fgauge-1.0.6.nightly-2019-07-25-windows.x86.exe>`__

.. cssclass:: dynamic-content windows content
`gauge-1.0.6.nightly-2019-07-25-windows.x86.zip <https://bintray.com/gauge/Gauge/download_file?file_path=windows%2Fgauge-1.0.6.nightly-2019-07-25-windows.x86.zip>`__

.. cssclass:: dynamic-content windows content
`gauge-1.0.6.nightly-2019-07-25-windows.x86_64.exe <https://bintray.com/gauge/Gauge/download_file?file_path=windows%2Fgauge-1.0.6.nightly-2019-07-25-windows.x86_64.exe>`__

.. cssclass:: dynamic-content windows content
`gauge-1.0.6.nightly-2019-07-25-windows.x86_64.zip <https://bintray.com/gauge/Gauge/download_file?file_path=windows%2Fgauge-1.0.6.nightly-2019-07-25-windows.x86_64.zip>`__