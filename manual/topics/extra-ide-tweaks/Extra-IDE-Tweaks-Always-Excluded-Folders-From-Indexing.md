<show-structure for="chapter,procedure,tab,def"/>

# Always Excluded Folders (From Indexing)

Define default Excluded Folders (not per-project). There is now a global list of excluded folders.

## Configuration

![](../../images/extra-ide-tweaks/extra-ide-tweaks-always-excluded-folders-cfg.png){ width="750" }

1. Enable the Always Excluded Folders feature.
2. Add some folders to exclude from indexing (relative paths).

## Usage

The configured paths are automatically added to the excluded folders list on project loading, and to all opened projects when modifying settings.

> Modifying the list of excluded folders can take too much time if you have many modules in your project (for example, IntelliJ Community sources contain 1300 modules), which would freeze the IDE.  
> To prevent that, and starting with Extra IDE Tweaks 2025.1.1 (also included in Extra Tools Pack 2025.1.1), the Always Excluded Folders feature ignores projects with more than 20 modules. A future update of the plugin will improve this.
{style="warning"}

In this example, the `node_modules` folder is automatically excluded, even if this folder doesn't exist yet.

![](../../images/extra-ide-tweaks/extra-ide-tweaks-always-excluded-folders.png){ width="720" }
