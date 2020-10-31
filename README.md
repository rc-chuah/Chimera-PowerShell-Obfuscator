# Chimera-PowerShell-Obfuscator
Chimera PowerShell Obfuscator

## Usage
### How To Use Chimera Online Version
1. Install Dependencies In Debian/Ubuntu/Kali/Parrot Sec OS Linux `sudo apt-get update && sudo apt-get install -Vy sed xxd libc-bin curl jq perl gawk grep coreutils git`
2. Install Dependencies In Termux `pkg update -y && pkg install -Vy sed curl jq perl gawk grep coreutils git`
3. Git Clone Repo `git clone https://github.com/rc-chuah/Chimera-PowerShell-Obfuscator`
4. Give execution permission `chmod +x chimera-online.sh`
5. Run script `./chimera-online.sh /path/to/input.ps1 /path/to/output.ps1`
### How To Use Chimera Offline Version
1. Install Dependencies In Debian/Ubuntu/Kali/Parrot Sec OS Linux `sudo apt-get update && sudo apt-get install -Vy sed xxd libc-bin curl jq perl gawk grep coreutils git`
2. Install Dependencies In Termux `pkg update -y && pkg install -Vy sed curl jq perl gawk grep coreutils git`
3. Git Clone Repo `git clone https://github.com/rc-chuah/Chimera-PowerShell-Obfuscator`
4. Give execution permission `chmod +x chimera-offline.sh`
5. Run script `./chimera-offline.sh /path/to/input.ps1 /path/to/output.ps1`

## So What's Are The Difference Between Chimera Online Version And Chimera Offline Version
#### The Difference Of The Online Version Of Chimera It Will Need Internet Access Every Time When You Run That Script.
#### The Difference Of The Offline Version Of Chimera It Will Need Internet Access Only Once When You Run That Script Then After That You Don't Need Internet Access To Run That Script.

## Quiet Mode
### How To Use Quiet Mode Chimera Online Version
1. Run script `./chimera-online.sh /path/to/input.ps1 /path/to/output.ps1 -q`
### How To Use Quiet Mode Chimera Offline Version
1. Run script `./chimera-offline.sh /path/to/input.ps1 /path/to/output.ps1 -q`

## Credits To The Original Creator:

Thanks To tokyoneon
