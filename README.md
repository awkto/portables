# How to Download via command line

Why do this? Sometimes you have read-only filesystems or non-privileged access to systems where you cannot properly download and install these tools. In those cases you can simply download these binaries and execute them.

One use cases is SUSE Harvester where the filesystem is read-only and you're not meant to be installing packaged locally.

Another use case is a system that did not have BZIP2 installed, so I could not download and extract the official BTOP packages from their releases.

## BTOP

### Btop via Curl
```
curl https://github.com/awkto/portables/releases/download/latest/btop -o btop
```

### Btop via Wget
```
wget https://github.com/awkto/portables/releases/download/latest/btop
```

## NEOFETCH
### Neofetch via Curl
```
curl https://github.com/awkto/portables/releases/download/latest/neofetch -o neofetch
```

## Neofetch via Wget
```
wget https://github.com/awkto/portables/releases/download/latest/neofetch
```
