/Let's install VS.code in LinuxMint.

Pass by Pass

1. Ctrl + Alt + T, open your prompt command.
2. Update system, type command: sudo apt update.
3. Upgrade system, type command: sudo apt upgrade.
4. Instal basics dependences, we need the "wget" to download files and the gpg to check our Micrsosoft Signature.
5. Add the key GPG oficial Microsoft, type the command: wget -qO- https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor | sudo tee etc/apt/trusted.gpg.d/microsoft.gpg > /dev/null, this keys ensures that the packages you download are actually from Microsoft(security).
6. 6. Add the VS.code repository, type command
