[![Build Status](https://travis-ci.org/JelteMX/mendix-dropdown-container.svg?branch=master)](https://travis-ci.org/JelteMX/mendix-dropdown-container)
[![Dependencies](https://david-dm.org/JelteMX/mendix-dropdown-container.svg)]([https://david-dm.org/JelteMX/mendix-dropdown-container](https://david-dm.org/JelteMX/mendix-dropdown-container))
[![DevDependencies](https://david-dm.org/JelteMX/mendix-dropdown-container/dev-status.svg)]([https://david-dm.org/JelteMX/mendix-dropdown-container?type=dev](https://david-dm.org/JelteMX/mendix-dropdown-container?type=dev))
[![Support](https://img.shields.io/badge/Support-Community%20(no%20active%20support)-orange.svg)](https://docs.mendix.com/developerportal/app-store/app-store-content-support)
[![Studio](https://img.shields.io/badge/Studio%20version-8.2%2B-blue.svg)](https://appstore.home.mendix.com/link/modeler/)
![GitHub release](https://img.shields.io/github/release/JelteMX/mendix-dropdown-container)
![GitHub issues](https://img.shields.io/github/issues/JelteMX/mendix-dropdown-container)

# Dropdown Container

Add Mendix elements to a dropdown container. Heavily based on [DropDownDivConverter](https://appstore.home.mendix.com/link/app/2089/), but an offline-capable pluginwidget that does it right. See it [in action here](https://dropdownpluginwidg-sandbox.mxapps.io)!

![AppStore](/assets/AppStoreIcon.png)

From Mendix 8.2.x and upwards it is possible to to add standard Mendix components to widgets. This Dropdown Container will behave as a dropdown button, but you can model the inside of the container using Mendix Studio Pro.

![Modeler](/assets/modeler.png)

## Features

- Put Mendix elements in a dropdown
- Split button, have an action button next to a dropdown indicator
- Button text is a dynamic text, you can use a text template (and attributes from your context)
- Standard Bootstrap styles (colors, sizes)

## Limitations

- In Mendix 8.2.2 it is not possible to use a snippet inside the dropdown container. **This is currently a limitation in the platform, not the widget.**
- It is not (yet) possible to model the content of the widget in Mendix Studio. This will hopefully be fixed in the future.

## Usage

Place the widget inside or outside a context object, based on if you need this for your buttonn text.

### General

![settings1](/assets/settings1.png)

- Button text is dynamic, meaning you can use attributes from a context object
- You can add a glyphicon to the left

### Appearance

![settings2](/assets/settings2.png)

### Split button

![settings3](/assets/settings3.png)

- If you would like to add an extra action to the dropdown, you can use a Split button.

## Demo project

Test-project can be found here: [https://dropdownpluginwidg-sandbox.mxapps.io](https://dropdownpluginwidg-sandbox.mxapps.io)

## Issues, suggestions and feature requests

Please report your issues/suggestions [here](https://github.com/JelteMX/mendix-dropdown-container/issues)

## License

Apache 2