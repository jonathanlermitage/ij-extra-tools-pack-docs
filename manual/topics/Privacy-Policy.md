<show-structure for="chapter,procedure,tab,def"/>

# Privacy Policy

**What is not sent?**

Extra Tools Pack, Extra Icons, Extra ToolWindow Colorful Icons and Extra IDE Tweaks plugins do NOT collect or store any personal data. All settings are stored locally, at IDE level and optionally at project level.

**What is the data sent?**

When the IDE starts up, certain technical and anonymous data may be collected. The installed plugin may transmit the following information:

| Property             | Description                                        | Example values                                                                                 |
|----------------------|----------------------------------------------------|------------------------------------------------------------------------------------------------|
| `id`                 | An ID generated for the system currently running.  | `86d883ab758c8bed3ea3cae3ec161683c305ba...`<br>*Data is hashed using SHA-512 before send*      |
| `ideName`            | The name of the IDE currently running.             | `IntelliJ IDEA`, `PhpStorm`, `Android Studio`                                                  |
| `ideVersion`         | The API version of the IDE currently running.      | `IC-251.27812.49`, `PS-261.22158.283`, `AI-253.30387.90`                                       |
| `pluginID`           | The ID of the plugin reporting the data.           | `lermitage.ij.all.pack`, `lermitage.ij.all.pack.lifetime`, `lermitage.ij.extra.icons.lifetime` |
| `pluginLicenseType`  | The license type of the plugin reporting the data. | `subscription`, `freemium`, `lifetime`                                                         |
| `pluginVersion`      | The version of the plugin reporting the data.      | `2026.1.6`, `2026.1.5`                                                                         |
| `pluginLicenseeName` | The name of the plugin license holder.             | `b79cfa128e34f18a949651408951889e795678...`<br>*Data is hashed using SHA-512 before send*      |

The sender's IP address is also collected on the server side.

This data is retained for a maximum of 31 days on a self-hosted server hosted by [Infomaniak](https://infomaniak.com), in Switzerland.  
This data is used to:
- determine which versions of the IDEs are in use. Anonymous statistics (i.e. counters) are available at [https://www.extratoolspack.com/api/stats_public.php](https://www.extratoolspack.com/api/stats_public.php) 
- assess whether it is worthwhile to continue supporting older IDE versions.
- detect and prevent fraud, such as the creation of illegal licenses or the sharing of licenses.  

This data is never shared with anyone. The endpoint is [https://www.extratoolspack.com/api/stats.php](https://www.extratoolspack.com/api/stats.php), in case that you're keeping a whitelist.

**How to disable data collection**

You can disable data collection by following these steps:
- Open your IDE
- Go to <ui-path>Help | Edit Custom Properties...</ui-path>
- Add this line: `extra-tools-pack.data-sharing=false`
- Restart your IDE

If you have any questions or concerns about my privacy practices, please contact me at *jonathan.lermitage AT gmail.com*.

**How to delete or reset your system ID**

The system `id` is automatically (re)created when running the IDE and Extra Tools Pack, Extra Icons, Extra ToolWindow Colorful Icons or Extra IDE Tweaks plugin is installed and enabled. It's located in a file you can freely delete:
* Windows: `APPDATA\JetBrains\Shared\extra-tools-pack-userid.txt`
* Linux: `~/.local/share/JetBrains/Shared/extra-tools-pack-userid.txt`
* macOS: `~/Library/Application Support/JetBrains/Shared/extra-tools-pack-userid.txt`

This path may differ for IDEs other than those from JetBrains, such as Android Studio.
