## Description

Connect to multiple VS Code devcontainers

## Guide

### To connect both:

1. VS Code run `Remote-Containers: Open Folder in Container...` from the Command Palette (`F1`) and select the `client` folder.

2. This will start up both containers and connect current window to service `client`.

3. Next, start up a new window using File > New Window.

4. In the new window, run `Remote-Containers: Open Folder in Container...` from the Command Palette (`F1`) and select the `server` folder.

5. Since the services are already running, VS Code will then connect to service `server`.

You can now interact with both containers at once from separate windows.

[Reference](https://code.visualstudio.com/remote/advancedcontainers/connect-multiple-containers)