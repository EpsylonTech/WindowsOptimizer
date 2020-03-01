# WindowsOptimizer
Epsylon Tech's recommended tools for optimizing Windows 10 for both performance and privacy.
## Getting Started
1. Download desired files from the `Download/` directory.
2. Ensure Powershell execution is allowed by running the following command in Powershell as administrator.
    ```
    PS> Set-ExecutionPolicy Unrestricted
    ```
3. Review the `RemoveBloatware.ps1` script to ensure that it will only remove apps you don't want. If you want to exempt a specific app, simply add a `#` before it to comment it out.
4. Run the `RemoveBloatware.ps1` script by right clicking on the script and selecting "Run in Powershell".
5. Double click on `ProtectPrivacy.reg` to disable activity tracking, Cortana, Bing search, and delivery optimization.
6. Double click on `GamingOptimization.reg` to give resource priorities to games and disable network throttling.

## Reverting Back
Most of the privacy settings can be reverted back under the Privacy Settings menu. However, restoring Cortana and Bing search requires registry edits. You can find restoration files under `Download/Restore/` directory. The `GamingOptimization.reg` can also be reverted back to default using the `RevertGamingOptimization.reg` file.


## Credits
I have referred to these repositories to spot check for bloatware apps I might have missed.
https://github.com/W4RH4WK/Debloat-Windows-10
https://github.com/Sycnex/Windows10Debloater
