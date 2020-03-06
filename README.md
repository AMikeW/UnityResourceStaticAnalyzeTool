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
 
# ABRedundency_2003042125  
资源名称 | 资源类型 | 资源大小 | AB文件数量 | AB文件名
---|---|---|---|---
Assets/Graphics/Home/arcade.png|UnityEngine.Sprite|107.0 KB|1|`D:/下载文件/游戏蛮牛源码/一个消消乐工程/Assets/StreamingAssets/333`
Assets/Graphics/Home/arcade_click.png|UnityEngine.Sprite|107.0 KB|1|`D:/下载文件/游戏蛮牛源码/一个消消乐工程/Assets/StreamingAssets/333`
Assets/Graphics/Home/background.png|UnityEngine.Texture2D|1.5 MB|1|`D:/下载文件/游戏蛮牛源码/一个消消乐工程/Assets/StreamingAssets/333`
Assets/Graphics/Play/JewelStar/4.png|UnityEngine.Texture2D|37.5 KB|1|`D:/下载文件/游戏蛮牛源码/一个消消乐工程/Assets/StreamingAssets/33333444`
Assets/Graphics/Play/JewelStar/2.png|UnityEngine.Texture2D|37.5 KB|1|`D:/下载文件/游戏蛮牛源码/一个消消乐工程/Assets/StreamingAssets/33333444`
Assets/Graphics/Play/Cell/cell_blue.png|UnityEngine.Texture2D|37.5 KB|1|`D:/下载文件/游戏蛮牛源码/一个消消乐工程/Assets/StreamingAssets/33333444`
Assets/Animations/CellChangeSprite.anim|UnityEngine.AnimationClip||1|`D:/下载文件/游戏蛮牛源码/一个消消乐工程/Assets/StreamingAssets/33333444`


## 3、分析UGUI合批情况
主要表现为如下图：
![](https://i.imgur.com/HlaQBul.png)

### 代表合批ID/UI深度/材质ID/贴图ID，暂不支持Mask、多材质、嵌套Canvas等情况
-----------------------
# 使用说明
![](https://i.imgur.com/P4Ss2On.png)
## 选中分析资源窗口，弹出一个窗口，点击窗口的对应按钮会导出相应的Excel文件。
## 选中分析AB包资源冗余，直接导出.md文件到工程目录Assets/AnalyzeABResource.md
## 选中Canvas，Hierarchy面板会出现【分析Canvas】按钮，点击它即可刷新UI的合批情况，最好在运行时进行检查，因为图集等情况会在运行时才加载。
