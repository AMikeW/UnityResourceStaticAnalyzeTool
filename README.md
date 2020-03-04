# UnityResourceStaticAnalyzeTool
分析Unity资源，如贴图、精灵图、旧版图集, 新版图集SpriteAtlas，支持分析AB包资源冗余 Analyze Unity Resources ,Such as Texture, Sprite, Prefab, SpritePacker, Sprite Atlas; Future, will support AssetBundle Resource Analyze. 

# 功能说明

## 1、分析工程内预制体依赖的资源，如贴图、精灵、图集，导出Excel如下图；
![Excel图](https://i.imgur.com/e4XKuOw.png)    
-------------------------
-----
![](https://i.imgur.com/nSBpucx.png)    
--------------
---------------------
![](https://i.imgur.com/9OsII7z.png)  
## 2、 分析工程AssetBundle包资源冗余情况，导出.md文件(MarkDown文件)  
# ABRedundency_2003042049  
资源名称 | 资源类型 | 资源大小 | AB文件数量 | AB文件名
---|---|---|---
Assets/Graphics/Home/arcade.png|UnityEngine.Sprite|0 B|1|`D:/下载文件/游戏蛮牛源码/一个消消乐工程/Assets/StreamingAssets/333`
Assets/Graphics/Home/arcade_click.png|UnityEngine.Sprite|0 B|1|`D:/下载文件/游戏蛮牛源码/一个消消乐工程/Assets/StreamingAssets/333`
Assets/Graphics/Home/background.png|UnityEngine.Texture2D|0 B|1|`D:/下载文件/游戏蛮牛源码/一个消消乐工程/Assets/StreamingAssets/333`
Assets/Graphics/Play/JewelStar/4.png|UnityEngine.Texture2D|37.5 KB|1|`D:/下载文件/游戏蛮牛源码/一个消消乐工程/Assets/StreamingAssets/33333444`
Assets/Graphics/Play/JewelStar/2.png|UnityEngine.Texture2D|37.5 KB|1|`D:/下载文件/游戏蛮牛源码/一个消消乐工程/Assets/StreamingAssets/33333444`
Assets/Graphics/Play/Cell/cell_blue.png|UnityEngine.Texture2D|37.5 KB|1|`D:/下载文件/游戏蛮牛源码/一个消消乐工程/Assets/StreamingAssets/33333444`

-----------------------
# 使用说明
![](https://i.imgur.com/P4Ss2On.png)
## 选中分析资源窗口，弹出一个窗口，点击窗口的对应按钮会导出相应的Excel文件。
## 选中分析AB包资源冗余，直接导出.md文件到工程目录Assets/AnalyzeABResource.md
