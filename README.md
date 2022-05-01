# Unity3D Web Player
此 Web 播放器修改自 7k7k.com 提供的 Unity3D 小游戏页面，并附带了一个忍者斩铁剑游戏（`game.unity3d`），将此文件替换为其他 `.unity3d` 文件即可播放你的自定义小游戏。

## 加载自定义游戏文件
1. 替换根目录中的 `game.unity3d` 文件。
2. 访问 `Player.html` 时追加参数 `?load=xxx.unity3d`，例如 `Player.html?load=newgame.unity3d`。支持使用相对路径和 URL 绝对路径，例如 `Player.html?load=../lego.unity3d`，`Player.html?load=http://flash.7k7k.com/cms/cms10/20130522/1531254229/dd/lego.unity3d`。

注意首次使用需要联网
