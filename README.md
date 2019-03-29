# VK Messenger Dark Theme

## Description

A dark style for [VK Messenger](http://VK.com/desktop-app) app from **Microsoft Store only**

## How to contribute

clone the repo, then:

1. `cd .\VK-Messenger-Dark-Theme`

2. `code .` (or any other code editor, even Notepad)

3. Make some changes in the .vktheme file, for example, change colors in the beginning of the file

4. Then save the file and go back to Powershell terminal.

5. Paste and execute

```Copy-Item .\VK-Messenger-Dark-Theme.vktheme -Destination "$Env:LOCALAPPDATA\Packages\C6965DD5.VKMessenger_v422avzh127ra\LocalCache\Roaming\VK\themes" -Force```


P. S. Command will replace the file on the destination folder without asking if it already exists.
