# KeyCounter 发布仓库

本仓库只存放 **键盘按键统计（KeyCounter）** 的免安装发布包与版本清单。
程序源码仓库为私有，这里提供可直接运行的 Windows 版本。

## 下载

到 [Releases](https://github.com/sherjor/KeyCounter-releases/releases/latest) 下载
`KeyCounter-*-win64.zip`，解压到任意目录，双击 `KeyCounter.exe`。

- Windows 10 / 11（64 位）
- 无需安装 Python
- 统计数据保存在程序旁的 `data\` 目录；卸载直接删除整个文件夹

## 功能

- 半透明圆角悬浮窗，实时显示本次 / 今日按键数，可切换迷你模式
- 概览、排行榜、按键明细、热力图（104 / 87 / 82 键）
- 今日 / 本周 / 本月 / 总计四种统计范围
- 日间 / 夜间主题、开机自启动、CSV 导出
- 只统计程序运行期间的按键，不记录输入内容，不联网

## 自动更新

程序内右键悬浮窗 →「检查更新」，或主界面左下角「检查更新」。
更新器从本仓库的 `latest.json` 读取版本，下载后校验 SHA-256 再替换文件；
统计数据保存在 `data\`，不会被覆盖。

## 许可与第三方

程序使用 [Bootstrap Icons](https://github.com/twbs/icons)（MIT）、
[HarmonyOS Sans SC](https://developer.harmonyos.com/cn/docs/design/des-guides/font-0000001157868583)
字体子集、[Pillow](https://github.com/python-pillow/Pillow)（HPND）等第三方资源，
随包保留相应声明。
