<show-structure for="chapter,procedure,tab,def"/>

# Getting Started

Extra IDE Tweaks provides the given features and workarounds:

- The [Open Editors](Extra-IDE-Tweaks-Open-Editors.md) tool window shows opened files in all editors belonging to the opened project, as in VSCode. It can also display a list of recently opened files, as in the Recent Files action.

- [Commit Alert](Extra-IDE-Tweaks-Commit-Alert.md): this inspection allows you to define keywords that will show a confirmation dialog before committing files containing any of those keywords. Per example, define the COMMIT_ALERT keyword, modify, delete or move one or multiple files containing it, then commit. A confirmation dialog will appear asking if you still want to commit.

- [Activate all tool windows](Extra-IDE-Tweaks-Activate-All-Tool-Windows.md): this action activates all the available tool windows in the current project. Enable it in settings, then see the <ui-path>Window | Activate All Tool Windows</ui-path> menu item. It is like clicking on the "..." button on the left-side toolbar, then clicking on each of the available tool windows.

- [Better Folder Icons](Extra-IDE-Tweaks-Better-Folder-Icons.md) can make folder icons more visible (with no outline style) when using the New UI. You can also use it with the [Classic UI](https://plugins.jetbrains.com/plugin/24468-classic-ui).

- [Better Tab Names](Extra-IDE-Tweaks-Better-Tab-Names.md) can rename tab names to remove the parenthesis after the filenames if they're located in the root project or module. Per example, renames `build.gradle.kts (my-module)` to `build.gradle.kts`. For now, it works with `build.gradle`, `build.gradle.kts`, `build.gradle.dcl`, `settings.gradle`, `settings.gradle.kts`, `settings.gradle.dcl` and `src/main/resources/META-INF/plugin.xml` files only.

- [Open a folder as a Project](Extra-IDE-Tweaks-Misc-Features.md) via the "Open In" menu.

- [Register any program and add it to the "Open In"](Extra-IDE-Tweaks-Add-Programs-To-Open-In.md) list when doing a right-click on a file, a folder, or a project. Your program will be added next to the <ui-path>Open In | Terminal</ui-path> action. That means you can open files and folders with your favorite program (like ForkLift, Total Commander, Vim...). You can register up to two "Open In" actions.

- [Change most tool windows label](Extra-IDE-Tweaks-Tool-Windows-Label-Override.md). Per example, rename the "Bookmarks" tool window to "Fav".

- [Confirm the opening of sensitive files](Extra-IDE-Tweaks-Confirm-Opening-of-Sensitive-Files.md). May be useful when streaming and/or accidentally opening a sensitive file in situations where you can leak critical information.

- [Define default Excluded Folders](Extra-IDE-Tweaks-Always-Excluded-Folders-From-Indexing.md) (not per-project). There is now a global list of excluded folders.

- [Open projects located in trusted locations](Extra-IDE-Tweaks-Trusted-Locations.md) directly via <ui-path>File | Trusted Locations</ui-path>, just after "Recent Projects".

- [Register your favorite projects](Extra-IDE-Tweaks-Favorite-Projects.md), organize them with optional groups, and gain fast access to your favorite projects via <ui-path>File | Favorite Projects</ui-path>, just after "Recent Projects" and "Trusted Locations".

- [Purge IDE's plugin download cache](Extra-IDE-Tweaks-IDE-Caches-Management.md), or its image cache only. This is a workaround for known IDE limitation 🐛 <a href="https://youtrack.jetbrains.com/issue/IJPL-6179/">IJPL-6179</a>.

- [Workaround](Extra-IDE-Tweaks-Workaround-for-Wrong-Version-Control-Label.md) for known IDE issue 🐛 <a href="https://youtrack.jetbrains.com/issue/IDEA-341174/Wrong-label-for-the-Git-toolwindow">IDEA-341174</a>: the Git tool window may display the wrong label "Version Control" instead of "Git".

- [Schedule the IDE's GC](Extra-IDE-Tweaks-GC-Scheduling.md).

- [Schedule the GC on local JVMs](Extra-IDE-Tweaks-GC-Scheduling.md). May be useful when having multiple Gradle or Kotlin Compiler daemons consuming too much memory. You can choose to run the GC on selected JVMs: all local JVMs, or by filtering by JVM instance name with your own regular expressions.

- Add a [Properties action](Extra-IDE-Tweaks-Misc-Features.md) to the File and Folder context menu that shows information like size, number of files, etc.

- Add a menu item under <i>Tools</i> in order to access the [Plugins Manager](Extra-IDE-Tweaks-Misc-Features.md) faster.
