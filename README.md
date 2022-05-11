# DTCD-PluginUpdater

DTCD-PluginUpdater - script for automatic update and download DataCAD projects.

## Getting Started

First you need to clone the DTCD-PluginUpdater. Then go to the project directory where the "PluginUpdater" script is located.

### Show help

```
./PluginUpdater -h
```

### Update DataCAD projects

Parameter `-d` is required.

```
./PluginUpdater -d "path/to/DataCAD"
```

### Choose custom JSON file

```
./PluginUpdater -d "path/to/DataCAD" --json "path/to/json"
```

## JSON file

JSON file (projects.json) contains the names of the repositories and their branches:

```
[
  {
    "repository": "DTCD",
    "branch": "develop"
  },
  {
    "repository": "DTCD-AppGUISystem",
    "branch": "develop"
  },
  
  ...
]
```

Fields ("repository" and "branch") in JSON file is required.

## Authors

Bragin Alexnadr [abragin@isgneuro.com](mailto:abragin@isgneuro.com)

## License

This project is licensed under the OT.PLATFORM license agreement - see the [LICENSE](LICENSE.md) file for details.
