# Launch Studio

A project I made to begin to learn C#. This won't work, and it's totally useless.

will **NOT** work since it gets the *specific* path for the studio launcher, which is a problem since roblox changes from folder to folder every new version.

```cs
var pathString = @"%USERPROFILE%\AppData\Local\Roblox\Versions\version-d6943a5e6de04dfb\RobloxStudioLauncherBeta.exe";
var filePath = Environment.ExpandEnvironmentVariables(pathString);
```
