# IDK
Zenburn Color Scheme for Processing

Attempted import of Zenburn to the Processing IDE

# Installation
Copy and replace all lines in ```%appdata%/Processing/preferences.txt``` containing ```editor.token``` with this code:
```
editor.token.comment1.style=#7F9F7F,plain
editor.token.comment2.style=#7F9F7F,plain
editor.token.function1.style=#efef8f,plain
editor.token.function2.style=#DFBE95,plain
editor.token.function3.style=#8DCBAC,plain
editor.token.function4.style=#53DCCD,bold
editor.token.invalid.style=#666666,bold
editor.token.keyword1.style=#f0dfaf,plain
editor.token.keyword2.style=#B3B784,plain
editor.token.keyword3.style=#8DCBAC,plain
editor.token.keyword4.style=#93A2CC,plain
editor.token.keyword5.style=#cedf99,plain
editor.token.keyword6.style=#f0dfaf,plain
editor.token.label.style=#666666,bold
editor.token.literal1.style=#cc9393,plain
editor.token.literal2.style=#edadad,plain
editor.token.operator.style=#F0EFD0,plain
```

And copy and replace all lines in ```[[your Processing folder]/lib/theme.txt``` below ```# foreground and background colors``` with this:
```
editor.fgcolor = #F6F3E8
editor.bgcolor = #404040
```
