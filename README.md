# qemu-img-binaries

Minimal set of files to run [`qemu-img`](https://qemu.readthedocs.io/en/latest/tools/qemu-img.html) on Windows.



## How to install

Simply `git checkout` this repository. All necessary files are included.

```powershell
git clone --quiet --depth 1 --single-branch 'https://github.com/fdcastel/qemu-img-binaries'
```



## Quick usage

This adds the latest version to your `TEMP` folder and add it to `PATH` of current session.

```powershell
$targetFolder = "$env:temp/qemu-img-binaries"
git clone --quiet --depth 1 --single-branch 'https://github.com/fdcastel/qemu-img-binaries' $targetFolder
$env:Path += ";$targetFolder"
```
