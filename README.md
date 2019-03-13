# APFS Mounter
A bash script work with apfs-fuse. It provide an easy way to mount APFS volumes.
  
## Usage
1. Make sure `apfs-fuse` is installed.
2. Copy `apfs-mounter` & `apfs-umounter` to `~/.local/bin`.
3. `chmod +x ~/.local/bin/apfs-mounter` & `chmod +x ~/.local/bin/apfs-umounter`
4. Copy the `.desktop` file to desktop.
5. Run the `.desktop` file and follow the instruction.
  
## What's working
* Search expected hard drive by size.
* Mount and unmount APFS volumes. (with or w/o password)
  
## What's currently NOT working
* Get an error when secified WRONG password for encrypted volumes. (`apfs-fuse` may freaked out and it just don't give any response)
