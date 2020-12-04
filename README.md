# WslDebugSample

This is a sample project running differently on WSL machine vs using WSL Debugging extension for VS.

# Running using [WSL 2 Plugin for Visual Studio](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.Dot-Net-Core-Debugging-With-Wsl2&ssr=false#overview)

When running this solution with the WSL 2 Plugin, the WslDebugSample.exe.nlog will log. Meaning a _log_ folder will be created in the _Debug/netcoreapp3.1/ubuntu-x64_ with two files in it.

# Running ssh Debugger manually

When Debuggung using the [launch.json](./launch.json) provided here, no log folder will be created. Of course to use the _launch.json_ on your machine, the ssh parameters need to be tweaked to match your WSL configuration. Advice on how to setup this type of debugging, see [here](https://medium.com/criteo-labs/wsl-visual-studio-attaching-launching-a-linux-net-core-application-on-my-window-10-ab21c179702d).
