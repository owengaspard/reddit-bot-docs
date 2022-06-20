# Installing SoX
SoX is a program that processes sound. As of version 2.0, SoX is required for the bot to function. Installing SoX is slightly more involved than just one command, but it is not difficult whatsoever.

## Windows

### Winget
Open Windows Terminal or PowerShell and run `winget install sox`. Afterwards, restart your shell of choice, and you should be good to go. If not, you may need to add SoX to your PATH. Instructions are below.

### Manual installation
1. Download Sox from [here](https://sourceforge.net/projects/sox/files/sox/) and run the installer.
2. Add SoX to your PATH. Instructions are below.
3. Restart your terminal, and you should be done.

![Windows Environment Variables - Credit to computerhope.com](https://www.computerhope.com/issues/pictures/win10-envirvariables.jpg)

### Adding SoX to PATH
1. Search for `Environment Variables` in Windows Search, and open it.
2. Click the button at the bottom to edit your environment vairables.
3. In the second panel, look for either `Path` or `PATH` on the left. Once you see it, click on it and then click `Edit`.
4. Click `Add` and paste the path to Sox (usually in `Program Files (x86)/sox-<version>`).
5. Click `Ok`. Restart your terminal, and you should be ready to use Sox.

## macOS
**(Recommended)** If you have Homebrew installed, run `brew install sox`. After, restart your terminal, and you should be off to the races. If you do not have Homebrew, installation instructions are provided below.

If you have MacPorts, run `sudo port install sox` and restart your terminal.

### Installing Homebrew on macOS

Install Homebrew by running this command in your terminal:

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

Once the process finishes, you can install SoX using the command above.

## Linux
Installing SoX on Linux is similar to the process for macOS, but the process will depend on your distro.

Debian/Ubuntu:

```
sudo apt install sox
```

Fedora/RHEL/CentOS

```
sudo yum install sox
```

Arch/Manjaro/Artix

```
sudo pacman -S sox
```

Gentoo

```
sudo emerge -q media-sound/sox
```

Afterwards, restart your terminal, and you should be good to go.