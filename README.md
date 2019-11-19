# scoop
scoop

# Initial
```scoop
scoop install 7zip curl sudo git openssh coreutils grep sed less
```

# color scheme
```scoop
scoop install concfg pshazz
concfg export theme-backup.json
concfg import solarized-dark
```

# Python
```scoop
scoop bucket add versions

scoop install python27 python
python --version # -> Python 3.x

# switch to python 2.7.x
scoop reset python27
python --version # -> Python 2.7.x

# swithc back (to 3.x)
scoop reset python

```

# vswhere
```scoop
scoop install vswhere
```
# Cascadia-Code
```scoop
scoop install Cascadia-code
```

# GCC
```scoop
scoop install gcc
```
