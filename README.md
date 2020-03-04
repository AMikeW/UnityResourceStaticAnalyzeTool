# UnityResourceStaticAnalyzeTool
分析Unity资源，如贴图、精灵图、旧版图集, 新版图集SpriteAtlas，后期支持AB包资源冗余 Analyze Unity Resources ,Such as Texture, Sprite, Prefab, SpritePacker, Sprite Atlas; Future, will support AssetBundle Resource Analyze. 

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
# ABRedundency_2003041937  
资源名称 | 资源类型 | AB文件数量 | AB文件名
---|---|---|---
Assets/Textures/AnimPic.jpg|UnityEngine.Texture2D|3|`E:/UnityProject/UGUI优化无限滚动列表/Assets/StreamingAssets/a.ab``E:/UnityProject/UGUI优化无限滚动列表/Assets/StreamingAssets/abc/c.ab``E:/UnityProject/UGUI优化无限滚动列表/Assets/StreamingAssets/b.ab`
Assets/Textures/Pic1.png|UnityEngine.Sprite|1|`E:/UnityProject/UGUI优化无限滚动列表/Assets/StreamingAssets/222`
Assets/Textures/Pic2.png|UnityEngine.Texture2D|1|`E:/UnityProject/UGUI优化无限滚动列表/Assets/StreamingAssets/222`
Assets/Prefabs/AB资源测试冗余/Sphere.prefab|UnityEngine.GameObject|1|`E:/UnityProject/UGUI优化无限滚动列表/Assets/StreamingAssets/a.ab`
Assets/Materials/Mat.mat|UnityEngine.Material|1|`E:/UnityProject/UGUI优化无限滚动列表/Assets/StreamingAssets/abc/c.ab`
Assets/Prefabs/AB资源测试冗余/WallBall.prefab|UnityEngine.GameObject|1|`E:/UnityProject/UGUI优化无限滚动列表/Assets/StreamingAssets/b.ab`

-----------------------
# 使用说明
![](https://i.imgur.com/P4Ss2On.png)
## 选中分析资源窗口，弹出一个窗口，点击窗口的对应按钮会导出相应的Excel文件。
## 选中分析AB包资源冗余，直接导出.md文件到工程目录Assets/AnalyzeABResource.md
