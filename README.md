# **Ultra Permissions DB Syntax**

> A [Visual Studio Code] extension that provides syntax highlighting for the [database] of [Ultra Permissions].

[![](https://vsmarketplacebadge.apphb.com/version-short/RLNT.uperms-db-syntax.svg)](https://marketplace.visualstudio.com/items?itemName=RLNT.uperms-db-syntax)
[![](https://vsmarketplacebadge.apphb.com/installs-short/RLNT.uperms-db-syntax.svg)](https://marketplace.visualstudio.com/items?itemName=RLNT.uperms-db-syntax)
[![](https://vsmarketplacebadge.apphb.com/rating/RLNT.uperms-db-syntax.svg)](https://marketplace.visualstudio.com/items?itemName=RLNT.uperms-db-syntax)

- [Discord]
- [Marketplace]

---

## **Features**

#### KEY FEATURES
- colors for
  - seperator symbols
  - mod identifiers
  - permissions
  - commands
  - wildcards
  - templates
- highlights incomplete or wrong lines

Example of a database entry:
![example]


## **Installation**

Go to the [Visual Studio Code Marketplace][Marketplace] and click the *install* button on the top of the site. You should be prompted to open Visual Studio Code in order to install the extension.<br>

You can also use the integrated extension browser in [VSCode][Visual Studio Code] to install it.


## **Usage**

Make sure to use a theme that supports this syntax highlighting. The theme we are using in our example is this one: [Material Dark Soda].<br>
To activate the syntax highlighting, your file needs to have the file extension `.updb`. If you did everything right, your permissions should be highlighted like in our example.

#### Highlighting
> the colors mentioned here can be different on the theme you are using

- yellow
  - the plugin name the permissions are for
  - turns red on mistakes
- green
  - the permission node of the plugin
  - turns red on mistakes
  - support placeholders (orange)
  - support wildcards (rose)
- white
  - description of the permission
- blue
  - the optional commands
  - turns red on mistakes
  - separated with commas (red)
    - turns purple on mistakes
  - support arguments (orange)
- pink
  - separators
- red
  - error color

## **Known Issues**

##### NOTHING KNOWN
- make sure to report issues in the [GitHub issues][Issues]
- you can also join our [Discord]


## **Contribution**

All you need to know is written down in our [contribution guidelines][Contribution].


## **License**

This project is licensed under the [MIT License][License].


## **Release Notes**

Everything related to versions and their release notes can be found in the [changelog][Changelog].

---

<!-- Links -->
[Visual Studio Code]: https://code.visualstudio.com/
[database]: https://github.com/TechsCode/PluginResources/blob/master/Permissions%20Database/Database.updb
[Ultra Permissions]: https://www.spigotmc.org/resources/ultra-permissions.42678/
[Semantic Versioning]: https://semver.org/
[Marketplace]: https://marketplace.visualstudio.com/items?itemName=RLNT.uperms-db-syntax
[Material Dark Soda]: https://marketplace.visualstudio.com/items?itemName=jbw91.theme-material-dark-soda
[Issues]: https://github.com/RLNT/vscode-uperms-db-syntax/issues
[Discord]: https://discordapp.com/invite/Q3qxws6
[Contribution]: CONTRIBUTING.md
[License]: LICENSE.md
[Changelog]: CHANGELOG.md

<!-- Images -->
[example]: https://raw.githubusercontent.com/RLNT/vscode-uperms-db-syntax/master/images/example.png
