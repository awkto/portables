# How to Download via command line

Why do this? Sometimes you have read-only filesystems or non-privileged access to systems where you cannot properly download and install these tools. In those cases you can simply download these binaries and execute them.

One use cases is SUSE Harvester where the filesystem is read-only and you're not meant to be installing packaged locally.

Another use case is a system that did not have BZIP2 installed, so I could not download and extract the official BTOP packages from their releases.

## Grab binaries with **curl**
```
curl https://github.com/awkto/portables/releases/download/latest/btop -o btop
curl https://github.com/awkto/portables/releases/download/latest/nano -o nano
curl https://github.com/awkto/portables/releases/download/latest/neofetch -o neofetch
curl https://github.com/awkto/portables/releases/download/latest/helm -o helm
curl https://github.com/awkto/portables/releases/download/latest/jq -o jq
curl https://github.com/awkto/portables/releases/download/latest/kubectl -o kubectl
```

## Grab binaries with **wget**
```
wget https://github.com/awkto/portables/releases/download/latest/btop
wget https://github.com/awkto/portables/releases/download/latest/nano
wget https://github.com/awkto/portables/releases/download/latest/neofetch
wget https://github.com/awkto/portables/releases/download/latest/helm
wget https://github.com/awkto/portables/releases/download/latest/jq
wget https://github.com/awkto/portables/releases/download/latest/kubectl
```
