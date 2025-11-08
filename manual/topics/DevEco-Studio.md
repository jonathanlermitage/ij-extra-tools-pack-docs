<show-structure for="chapter,procedure,tab,def"/>

# Huawei DevEco Studio

[Huawei DevEco Studio](https://developer.huawei.com/consumer/en/deveco-studio/) is the official IDE for Huawei's HarmonyOS operating system. It is based on IntelliJ IDEA Community (with some modifications) and includes additional features provided by Huawei.

## DevEco Studio support

DevEco Studio 5 (**at least version 5.1.1.850**) is officially supported by Extra Tools Pack, Extra Icons, Extra ToolWindow Colorful Icons and Extra IDE Tweaks.

DevEco Studio 6 will also be officially supported once it's available outside from China. For now, you should be able to use it, but I can promise nothing.  
If you have access to DevEco Studio 6, I would be happy to read your feedback. At least, you would help me a lot by going to <ui-path>Help | About DevEco Studio | Copy and Close</ui-path>, paste to a text file, and send me this file (jonathan.lermitage AT gmail.com). This will tell me what's the [base version](#how-to-find-the-base-version-of-deveco-studio) of DevEco Studio 6.

### Plugin installation

You have to download the plugin file from the JetBrains marketplace:

- Navigate to the plugin page:
  - [Extra Tools Pack](https://plugins.jetbrains.com/plugin/24559-extra-tools-pack/versions)
  - [Extra Icons](https://plugins.jetbrains.com/plugin/11058-extra-icons/versions)
  - [Extra ToolWindow Colorful Icons](https://plugins.jetbrains.com/plugin/16604-extra-toolwindow-colorful-icons/versions)
  - [Extra ToolWindow Colorful Icons Lifetime](https://plugins.jetbrains.com/plugin/26404-extra-toolwindow-colorful-icons-lifetime/versions)
  - [Extra IDE Tweaks](https://plugins.jetbrains.com/plugin/23927-extra-ide-tweaks/versions)
  - [Extra IDE Tweaks Lifetime](https://plugins.jetbrains.com/plugin/27808-extra-ide-tweaks-lifetime/versions)
- Go to the **Versions** tab.
- Download a plugin version that is compatible with your DevEco studio version. Look at the **Compatibility Range** column, then use the corresponding **Download** link. For information: 
  - DevEco Studio 5.1.1 is based on 2023.3 IDEs.
  - DevEco Studio 6 should be based on 2024.1 or 2024.3 IDEs (I have no access to DevEco Studio 6 for now).
- Install the downloaded ZIP file manually in DevEco Studio: <ui-path>File | Settings | Plugins | Install Plugin from Disk...</ui-path>, and select the ZIP file.
- Restart DevEco Studio.

> My plugins are not (yet) listed in the plugin browser built into DevEco Studio, because Huawei uses a whitelist of plugins, and I am having difficulty getting approval from their support team. This is why you have to install them manually. 
> 
> If Huawei finally accepts my request, you will see my plugins directly in the plugin browser of DevEco Studio, as in JetBrains IDEs and Android Studio. 
> 
> I apologize for the inconvenience.
{style="warning"}

#### How to find the base version of DevEco Studio

DevEco Studio is based on IntelliJ Community. To find its version, go to <ui-path>Help | About DevEco Studio | Copy and Close</ui-path>, paste its content to a text file (of simply print it in a terminal). You will get something like this:

```
DevEco Studio 5.1.1 Release  
Build #DS-233.14475.28.36.511840  
(...)
Registry:
  idea.plugins.compatible.build=IC-233.14475.28
(...)
```

The first line is the version of DevEco Studio.  
The second line is the base version of IntelliJ Community.

Here, `233` is the base version of IntelliJ. The two first digits `23` are for `2023`, and the third digit `3` for `.3` In other words, in this example, we can see DevEco Studio 5.1.1 is based on IntelliJ Community 2023.3.  
The line `idea.plugins.compatible.build=IC-233.14475.28` should confirm that: it is used by the IDE to filter compatible plugins (`IC` is for IntelliJ Community, and you know what `233` means).

For DevEco Studio 6, you may see `241` or `243`, which means 2024.1 or 2024.3.


### License activation

You need to use an **offline activation code** because DevEco Studio does not support JetBrains authentication. To proceed:

- Visit your JetBrains profile: [https://account.jetbrains.com/licenses](https://account.jetbrains.com/licenses), scroll to the plugin you want to activate, and click on **Download a code for offline activation**. Open the downloaded ZIP file. It contains a text file: open it and copy its content. This is your offline activation code.
  
![](../images/general/offline-activation-code.png){ width="680" }

- In DevEco Studio, go to <ui-path>Help | Register Plugins...</ui-path>, select the plugin you want to activate, click on **Activation code**, then paste your offline activation code, click on **Activate**.

![](../images/general/offline-activation-code-2.png){ width="680" }

- Restart DevEco Studio.
  > Due to limitations of the JetBrains APIs, you may have to restart DevEco Studio twice the first time you activate your offline activation code. This scenario may happen one time only, and it can affect only the features from Extra ToolWindow Colorful Icons. Most users shouldn't face this issue. I apologize for the inconvenience.
