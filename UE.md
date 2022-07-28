# UnrealEngine

## UE5

[UE5已正式发布（2022.04.05）](./UE5.md)


## Install

Search：`[InstalledDerivedDataBackendGraph]`

in BaseEngine.ini
```
Local=(Type=FileSystem, ReadOnly=false, Clean=false, Flush=false, PurgeTransient=true, DeleteUnused=true, UnusedFileAge=34, FoldersToClean=-1, Path="E:\Unreal Engine\ENGINEVERSIONAGNOSTICUSERDIR\DerivedDataCache", EditorOverrideSetting=LocalDerivedDataCache)
```
->
```
Path="%GAMEDIR%DerivedDataCache"
```


## Study

> https://learn.unrealengine.com/home


dashboard.

## Tools

## Bridge

有一些免费材质


## Mixer

材质合成软件，


### World Creator

- 软件下载

> https://pan.baidu.com/s/1mZ3aMRMowSCoTAKlFAyTqg
> 提取 r3yu

- 使用方法

https://www.bilibili.com/video/BV1cA411L71h?spm_id_from=333.337.search-card.all.click

### Global Mapper

- 地理空间数据云构建灰度图

> https://www.bilibili.com/video/BV1oA411J7g3?spm_id_from=333.337.search-card.all.click

- 延伸阅读

> 参考视频1 https://www.bilibili.com/video/BV1jE411h7Rm?from=search&seid=9026152909523570327
> 参考视频2 https://www.bilibili.com/video/BV1xz4y1Q7Vc?from=search&seid=3889288635838530262

Globel mapper 软件下载在第一个参考视频简介中，第2个参考视频里有详细的导入后地形处理教程，


### OpenStreetMap

> https://www.openstreetmap.org


- CityEngine 导入 OSM数据（这个只是建模）

> https://blog.csdn.net/ZJ_____W/article/details/105745447


### Houdini 对 OSM 数据进行城市建模（可导入到UE）


> https://www.sidefx.com


- 城市建模示例

> https://www.bilibili.com/video/BV1F64y187yc?spm_id_from=333.337.search-card.all.click
> https://www.youtube.com/watch?v=8YDWj0-QFVQ

### UE4虚幻引擎城市建筑包

> https://www.youtube.com/watch?v=PSvIoUGG_Ss

用城市建筑包从模块化资产中构建具有照片真实感的城市。该包附带了一个现成的示例场景，显示了如何创建自己的城市。该软件包提供了城市锁和独立建筑的拖放预设。每个建筑都是一个结合了多个模块网格的蓝图。这允许直接编辑建筑，包括更改楼层数、添加装饰元素和更改材质。先进的母材可以快速方便地修改建筑物和道具的外观，很好的结合了刷风景。


## Addons


### Quixel

> https://quixel.com/




### Cesium for Unreal

> https://vimeo.com/529842190

Cesium for Unreal插件解锁了虚幻引擎的3D地理空间生态系统。它将一颗高精度的WGS84地球、开放API、空间索引开放标准（如3D Tiles）、基于云端的真实世界3D内容与虚幻引擎的力量相结合，将为你开启一个使用游戏引擎创建地理空间应用，并利用真实世界内容的新时代。

示例： https://www.unrealengine.com/marketplace/en-US/product/c6639cbe970b4126847049944709a27a

### cesium ion

> https://cesium.com/ion
