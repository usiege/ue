# UnrealEngine

## UE5

[UE5已正式发布（2022.04.05）](./UE5.md)


## Install

Search：`[InstalledDerivedDataBackendGraph]`[

in BaseEngine.ini
```
Local=(Type=FileSystem, ReadOnly=false, Clean=false, Flush=false, PurgeTransient=true, DeleteUnused=true, UnusedFileAge=34, FoldersToClean=-1, Path="E:\Unreal Engine\ENGINEVERSIONAGNOSTICUSERDIR\DerivedDataCache", EditorOverrideSetting=LocalDerivedDataCache)
```
-> 
```
Path="%GAMEDIR%DerivedDataCache"
```

## Addons


### Cesium for Unreal

> https://vimeo.com/529842190

Cesium for Unreal插件解锁了虚幻引擎的3D地理空间生态系统。它将一颗高精度的WGS84地球、开放API、空间索引开放标准（如3D Tiles）、基于云端的真实世界3D内容与虚幻引擎的力量相结合，将为你开启一个使用游戏引擎创建地理空间应用，并利用真实世界内容的新时代。

示例： https://www.unrealengine.com/marketplace/en-US/product/c6639cbe970b4126847049944709a27a

### cesium ion

> https://cesium.com/ion

