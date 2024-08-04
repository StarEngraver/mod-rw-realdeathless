# mod-rw-realdeathless

RealDeathless: A new archite gene makes your pawn never die.

## Info

This repository is used to store all files that related to the project: mod-rw-realdeathless, including but not limited to source code, binary or other peripheral documents.

## Intro

### Features

- Restore missing parts every 60000 ticks (1 day).
- Cure injures and wounds every 60000 ticks (1 day).
- Resurrect from death like collapsed rocks (only player).
- Pawn's HP will not lower than 5% (only player, optional).

### Localization

- English
- Simplified Chinese

### Compatibility

- Game Version: `1.4.3901`, `1.5`

### Instructions

#### Local Use

Windows CMD - Administrator

```cmd
mklink /d "[PATH TO STEAM]\steamapps\common\RimWorld\Mods\RealDeathless" "[PATH TO LOCAL REPO]\mod-rw-realdeathless\mod"
```

#### Steam Workshop

[Workshop: RealDeathless](https://steamcommunity.com/sharedfiles/filedetails/?id=2931523061)

### Build Legacy Assemblies

#### 1.4

Dev Container Shell

```shell
dotnet build /workspaces/mod-rw-realdeathless/src/CodeArchived/1.4/Code/lib-mod-rw-realdeathless.sln /property:GenerateFullPaths=true /consoleloggerparameters:NoSummary /p:Configuration=Debug /p:Platform="Any CPU"
```

## Acknowledgments

- [RimWorld](https://store.steampowered.com/app/294100/RimWorld) by [Ludeon Studios](https://ludeon.com)
- [Docker](https://www.docker.com)
- [.NET](https://dotnet.microsoft.com/en-us/download/dotnet)
- [NuGet](https://www.nuget.org) Packages: [Krafs.Rimworld.Ref](https://www.nuget.org/packages/Krafs.Rimworld.Ref), [Lib.Harmony](https://www.nuget.org/packages/Lib.Harmony)
- [VS Code](https://code.visualstudio.com) with Required Extensions: [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers), [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig), [C# Dev Kit](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit), [XML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml)
