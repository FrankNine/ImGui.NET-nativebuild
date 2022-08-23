# To Update to the latest cimgui version

```
git submodule update --init
git submodule update --remote
```

and then git commit + push.

# To Trigger a release push a tag as shown below

```
git tag -a v1.4 -m "my version 1.4"
git push origin v1.4
```

# Modification
Building cmake with `-G "Visual Studio 17 2022"`

Required Visual Sutio 2022 Install:
* C++ CMake tools for Windows
* MSVC v143 - VS 2022 C++ x64/x86 build tools
* MSVC v143 - VS 2022 C++ ARM build tools
* MSVC v143 - VS 2022 C++ ARM64 build tools