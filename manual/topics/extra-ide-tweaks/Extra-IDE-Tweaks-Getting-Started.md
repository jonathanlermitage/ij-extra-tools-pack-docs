<show-structure for="chapter,procedure,tab,def"/>

# Getting Started

Extra IDE Tweaks provides the given features and workarounds:

<ul>
    <li>The <b>Open Editors</b> tool window shows opened files in all editors belonging to the opened project, as in VSCode. It can also display a list of <b>recently opened files</b>, as in the Recent Files action.</li>
    <li>Can <b>make folder icons more visible (with no outline style)</b> when using the New UI. You can also use it with the regular UI.</li>
    <li>Can <b>change most tool windows label</b>. Per example, rename the "Pull Requests" tool window to "PR".</li>
    <li>Can <b>confirm the opening of sensitive files</b>. May be useful when streaming and/or accidentally opening a sensitive file in situations where you can leak critical information.</li>
    <li>Can <b>open projects located in trusted locations directly via File > Trusted Locations</b>, just after Recent Projects.</li>
    <li>Can <b>register your favorite projects, organize them with optional groups</b>, and gain fast access to your favorite projects via File > Favorite Projects, just after Recent Projects and Trusted Locations.</li>
    <li>Can <b>define default Excluded Folders (not per-project)</b>. There is now a global list of excluded folders. Go to Extra IDE Tweaks settings for details.</li>
    <li><b>Commit Alert</b>: this inspection allows you to define keywords that will show a confirmation dialog before committing files containing any of those keywords. Per example, define the COMMIT_ALERT keyword, modify, delete or move one or multiple files containing it, then commit. A confirmation dialog will appear asking if you still want to commit.</li>
    <li><b>Activate All Tool Windows</b>: this action activates all available tool windows in the current project. Enable it in settings, then see the "Window > Activate All Tool Windows" menu item. It's like clicking on the "..." button on the left-side toolbar, then clicking on each available tool window.</li>
    <li>Can <b>register any program and add it to the "Open In" list</b> when doing a right-click on a file, a folder, or a project. Your program will be added next to the "Open In" <i>Terminal</i> action. That means you can open files and folders with your favorite program (like ForkLift, Total Commander, Vim...). You can register up to 2 "Open In" actions. Go to Extra IDE Tweaks settings for details.<br/>
        You can also <b>open files with Associated Application</b>. This additional action is enabled for IDEs prior to 2024 only, as it is already implemented by 2024+ IDEs.</li>
    <li>Can <b>open a folder as a Project</b> via the "Open In" menu.</li>
    <li>Can rename tab names to <b>remove the parenthesis after the file names</b> if they're located in the root project or module. Per example, renames "build.gradle.kts (my-module)" to "build.gradle.kts". For now, it works with "build.gradle", "build.gradle.kts", "build.gradle.dcl", "settings.gradle", "settings.gradle.kts" "settings.gradle.dcl" and "src/main/resources/META-INF/plugin.xml" files only.</li>
    <li>Can <b>purge IDE's plugin download cache</b>, or its image cache only. This is a workaround for known IDE limitation 🐛 <a href="https://youtrack.jetbrains.com/issue/IJPL-6179/">IJPL-6179</a>.</li>
    <li>Can <b>schedule the IDE's GC</b>.</li>
    <li>Can <b>schedule the GC on local JVMs</b>. May be useful when having multiple Gradle or Kotlin Compiler daemons consuming too much memory. You can choose to run the GC on selected JVMs: all local JVMs, or by filtering by JVM instance name with your own regexes.</li>
    <li>Adds a <b>Properties</b> action to the File and Folder context menu that shows information like size, number of files, etc.</li>
    <li>Adds a menu item under <i>Tools</i> in order to <b>access the Plugins Manager faster</b>.</li>
    <li>Offers a workaround for known IDE issue 🐛 <a href="https://youtrack.jetbrains.com/issue/IDEA-341174/Wrong-label-for-the-Git-toolwindow"><b>IDEA-341174</b></a>: the Git tool window may display the wrong label "Version Control" instead of "Git".</li>
</ul>
