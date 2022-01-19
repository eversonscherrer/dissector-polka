# PolKA Wireshark Dissector
DIssector for wireshark with lua to the Polinomial Key Protocol (PolKA)

## Linux Installation

### Create the LUA Plugin folder
Help > About > Folders

### Create manualy the LUA Plugin folder
```zsh
mkdir /home/$USER/.local/lib/wireshark/
cd /home/$USER/.local/lib/wireshark/
```

### Download the PolKA Wireshark Dissector 
```zsh
wget https://raw.githubusercontent.com/eversonscherrer/dissector-polka/main/polka_dissector.lua
```

### Reload LUA Plugins
`Analyze > Reload LUA Plugins` or `Ctrl + Shift + L` 

## Mac Installation

About > Folders
