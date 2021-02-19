```
.
├── controllers
├── libraries
├── plugins
│   ├── physics
│   ├── remote_controls
│   └── robot_windows
├── protos
└── worlds
    └── IDP_L2_v10.wbt
```

# Instructions for basic submodule usage
To fetch submodules (after cloning this repo)
```
git submodule update --init
```
To add a submodule
```
git submodule add https://github.com/IDP-L211/repo-name
```
To update all submodules to the latest commit
```
git submodule update --remote
```
To completely remove a submodule (yes it is this annoying)
```
git submodule deinit repo-name
# now delete the relevant lines in .gitmodules
rm -rf .git/modules/repo-name
```
