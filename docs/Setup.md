# Setup

## Install

There are several options available to install ElectronIM

### Platform packaged ElectronIM

Download the latest release for your platform from our releases page:
https://github.com/manusa/electronim/releases/latest

Extract the compressed file for your platform into a directory.

Run the appropriate executable in the extracted directory for your platform:

* Windows: `electronim.exe`
* MacOS: `electronim.app`
* Linux: `electronim`

### [Snapcraft](https://snapcraft.io/electronim) package

A Snap package is available for systems with `snapd` installed.
Snapcraft is installed by default in Ubuntu, but is also available for most Linux distributions
(check Snapcraft website for the [installation guide](https://snapcraft.io/docs/installing-snapd) for your platform).

Once snapd is installed in your system, run the following command to install ElectronIM:

```
sudo snap install electronim
```

## Settings

The first time you open the application you'll be presented with the settings dialog
where you can add the services you'll be using:
![Settings](screenshots/settings-empty.png)

Insert a valid URL into the empty text-field and press enter to add the new entry.

Repeat this process for each service you want to add.

## Spell checker

Select the applicable check-boxes to enable the spell checker for the selected languages.

Finally press **Ok** to confirm your settings, the application will reload with the added services.
