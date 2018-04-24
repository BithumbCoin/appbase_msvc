# appbase_msvc

appbase Microsoft Visual Studio 2017 solution

## Dependencies

- Microsoft Visual C++ 2015 or newer
- Boost 1.60 or newer compiled with C++14 support

## Usage

- One plugin

```ps1
> .\App.exe --plugin net_plugin
```

```ps1
initialize chain plugin
initialize net plugin
starting chain plugin
starting net plugin
shutdown net plugin
shutdown chain plugin
exited cleanly
```

- Tow plugin

```ps1
> .\App.exe --plugin net_plugin --plugin chain_plugin
```

```ps1
initialize chain plugin
initialize net plugin
starting chain plugin
starting net plugin
shutdown net plugin
shutdown chain plugin
exited cleanly
```