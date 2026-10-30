# 水墨江湖 · Ink & Blade —— 试玩版发布页

这里只存放《水墨江湖》试玩版的**安装包和更新包**，不包含源代码。

## 下载安装

到 [Releases 页面](https://github.com/2954130841/wuxia-demo-releases/releases/latest) 下载对应系统的完整包：

| 系统 | 文件 |
|---|---|
| Windows 10/11 (64 位) | `ShuimoJianghu_demo_win64.zip` |
| macOS 11+（Intel / Apple 芯片） | `ShuimoJianghu_demo_macos.zip` |
| Linux x86_64 | `ShuimoJianghu_demo_linux64.zip` |

解压后运行即可，无需安装。压缩包内附「玩法说明.txt」（操作说明、存档位置）。

- **Windows**：首次运行若出现「Windows 已保护你的电脑」，点「更多信息」→「仍要运行」（程序未做付费签名）。
- **macOS**：右键 App →「打开」→「打开」；若提示“已损坏”，在终端执行 `xattr -dr com.apple.quarantine "水墨江湖 · Ink & Blade.app"`。

## 自动更新

游戏每次启动会自动检查这里的最新版本：有新版本时显示更新内容并下载更新包（`game_<版本>.pck`），校验无误后自动重启进入新版本。
- 没网或下载失败时直接用本地版本进入游戏，不影响游玩。
- 存档不会被更新动到。
- 可在游戏「设置」里关闭自动检查，或手动点「检查更新」。
- 若提示需要下载新的完整包，重新下载上面的 zip 即可（存档保留）。

`manifest.json` 是给游戏内更新器读取的版本信息文件。
