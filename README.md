# Chirpware
Joke tray app made purely in Python made for me and my friend that plays a sound effect every set interval of time

Key things I learned:

- some incredibly surface level threading stuff (needed to interrupt the wait when the setting is changed or a quit is requested)
- working with pystray and pillow (very minimally though)
- working through pyinstaller

Left to learn:
- working with the registry via winreg (for the WIP setting 'start on boot' and to store current selected frequency index)
- doing http requests to fetch the latest update, updating the standalone exe (so far I've only a hacky idea of downloading it to %temp%, then using an invisible terminal window to replace it and restart it)
