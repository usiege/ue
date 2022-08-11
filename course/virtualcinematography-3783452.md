# 虚拟制片简介

> https://learn.unrealengine.com/course/3783452


## 灵感启发

> www.shotdeck.com

## 创建摄像机

1. `~`键打开控制台，搜索`ForceAllRayTracingEffects`命令（光线追踪效果）；

2. cine Camera Actor 摄像机Actor；
3. `G`游戏模式，可以隐藏所有不可见的部分；


## 感应器大小

> www.vfxcamdb.com

## 焦距和视野
暂无内容

## 光圈和景深
暂无内容

## 自动调焦

1. 将一个空的Actor绑定到你想拍摄的对象上，使用焦点追踪无缝转换焦点;
2. 设置蓝图，添加骨骼，拖放到父Actor上；

## 曝光

> Tips：shift + 点击世界大纲文件夹处的小键头，可以快速折叠文件夹；

1. Post process volume，后期处理体积设置曝光；
2. Details中，unbound 影响无限范围；
3. 后期处理体积用来影响世界，摄像机用来影响焦点；
4. 快门48，ISO800，exposure3.0设置摄像机；
5. motion，后期处理体积动态模糊效果；

## Sequencer

1. 你可以将帧率设置成24fps，使它看起来更像电影；
2. 按键S可以为所有轨道设置当前为关键帧；
3. 使用关键帧来进行镜头移动和焦点移动；
4. liner线性选项可以让镜头切换更加平滑；


## 摇臂和轨道
