# VSCode/tsserver.js Bug Case
When multiple files with name `Index.ts` or `Index.tsx` are opened in VS Code, compile errors appear to stop being reported in all but the first session started.

### Demo:

![bug demonstration](https://dl.dropboxusercontent.com/s/0pe2rgt52wnw4qu/tsserver-bug-steps.gif)

### Builds tested:
```
[Window Title]
Visual Studio Code - Insiders

[Main Instruction]
Visual Studio Code - Insiders

[Content]

Version 1.5.0-insider
Commit 2f2d6502638fa108f8ddbcc5831b38a35d5a1c11
Date 2016-08-25T06:09:29.461Z
Shell 0.37.6
Renderer 49.0.2623.75
Node 5.10.0

[OK]
```

```
[Window Title]
Visual Studio Code

[Main Instruction]
Visual Studio Code

[Content]

Version 1.4.0
Commit 6276dcb0ae497766056b4c09ea75be1d76a8b679
Date 2016-08-04T16:45:31.680Z
Shell 0.37.6
Renderer 49.0.2623.75
Node 5.10.0

[OK]
```