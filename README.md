# slock
Simple X display locker. (by suckless) [customized]


Original: https://tools.suckless.org/slock/

## Patches/Customizations in use
- Blur


## Patching process
My patching strategy:
    upstream branch is pulled and in sync with suckless upstream
    master is my normal current running version
    dev is the testing version

to apply a new patch:
    checkout upstream
    branch upstream to newpatch
    apply patch to newpatch name
    commit and push, resolving any conflicts
    checkout dev
    merge newpatch, resolving any conflicts
    push dev
    test stdevage branch for functionality
    merge dev into master
    test master

## additional prereq packages
libxrandr-dev
