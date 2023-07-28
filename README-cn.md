## [VivalArc](https://arc.tovi.fun)
这个项目主要包含一套 CSS 文件和一个 Vivaldi 主题。通过几步简单的设置，可以将 Vivaldi 魔改成 Arc。

[📺设置方式-视频版](https://www.bilibili.com/video/BV1fe4y1a7WQ) | [📝英文介绍和配置方式](./README.md) | [🧑‍💻更新日志](./docs/changelog-cn.md)

![截屏预览](assets/vivalarc_screenshot.jpg)

## 💡 **几点说明：**

1. 它的本质是使用 Vivaldi 浏览器的自定义 UI MOD 的功能改变外观（结合这个配置中你将要下载的 CSS），整个配置过程大约5分钟
2. 这个配置在 Windows 上也可以使用。在接下来设置快捷键的过程中，只需要将 `Command` 换成 `Ctrl`。（[有用户反馈  Linux 上也能使用](https://twitter.com/vivaldi_fr/status/1684643796942815233) ，但是我没自己去试过）
3. Vivaldi 是基于开源的 Chromium，所以理论上网页浏览效果是和 Chrome、 Edge 一样的
4. 如果在使用的过程中，遇到了问题浏览器 UI 问题（因为这个配置只会改到UI，其它的问题反馈就不用找我啦），可以在以下几个地方反馈
    - 在 Github 提 Issue
    - [在 Bilibili 下方评论或者给我私信](https://www.bilibili.com/video/BV1fe4y1a7WQ/)
    - [在 Twitter 的这条Po文上评论](https://twitter.com/tovizhong/status/1563447293600493569)
5. 如果想返回原来的效果，只需要将关闭「允许使用自定义 CSS 自定义 UI」的实验性功能关闭（后面的设置中会详细说明）
6. 在添加 CSS 的时候我只知道如何改变元素样式和隐藏元素，如果你知道如何实现更好的效果，可以跟我分享一下你的CSS😂

---

## 🛠️ 开始配置吧！

### 第一步：安装Vivaldi浏览器

- 因为这本质还是Vivaldi浏览器，所以第一步，去安装一个[Vivaldi浏览器](https://vivaldi.com)吧。如果你之前没用过这个浏览器，可以去它的官网看看，了解它的更多功能。
- 如果你需要在多个设备上使用 Vivaldi，可以先注册一个 Vivaldi 帐号，用来同步书签、设置、密码、历史记录、插件等数据。

### 第二步：打开浏览器的设置

> 设置过程中时候，可以在`设置`页左上角进行搜索关键词快速定位
- **外观** > **状态栏** > 选择`悬浮状态栏`
- **标签** > **标签栏位置** > 选择`左侧`
- **标签** > **标签组** > 选择 `紧凑`、`折叠式` 或者 `禁用`（重要，总之不要用`两级`，因为`两级`这个我没调整它的样式）
- **面板** > **面板选项** > 勾上`悬浮面版`
- **面板** > **面板位置** > 选择`右侧`（左侧也可以，但是左侧是标签栏的位置，比较重度交互的区域，可能会有不可预见的Bug，所以推荐放在右侧和标签栏分开）
- **地址栏** > 去掉`显示地址栏`
- **快捷命令** > 将`在新标签页打开链接`勾上
- **键盘**(设置必要的快捷键)
    - **新建标签** > 移除「新建标签」的快捷键
    - **快捷命令** > 在原来基础上加上 `Command + T`
    - **页面另存为** > 移除「页面另存为」的快捷键
    - **标签栏** > `Command + S`
    - **地址栏** > `Command + B`（Windows下需先移除「书签」的快捷键）
    - **创建书签** > 移除「创建书签」的快捷键
    - **固定 / 取消固定标签** > `Command + D`
    - **打印** > 移除「打印」的快捷键
    - **面板** > 在原来基础上加上 `Comand + P`

### 第三步：自定义 UI MOD

- [下载这个文件](https://github.com/tovifun/VivalArc/archive/refs/heads/main.zip)，解压保存在一个你不会删除的地方
- 主题 > 打开主题 >  选择 ArcLight.zip 主题
- 打开 `vivaldi://experiments` 并开启  `"Allow for using CSS modifications"`
- 打开设置 > 外观 > `自定义UI MOD`
- 选择文件夹 > 选择刚才解压的文件夹
- 重启 Vivaldi，这时你应该可以看到你的浏览器效果跟我上方的图片效果一样了
- 换一张你喜欢的壁纸，你刚解压的文件夹里我放了几张进去，可以换上看看

---

## 💌 感谢
- [@clementpoiret](https://github.com/clementpoiret) 添加了 [ArcDark 主题](https://github.com/tovifun/VivalArc/pull/5)

---

## 🧑‍💻 来自用户的截屏：
- Twitter [@vivaldi_fr](https://twitter.com/vivaldi_fr/status/1684643796942815233)
- Github [@clementpoiret](https://github.com/tovifun/VivalArc/pull/5)

---

## 相关链接

- **Arc评测：**[https://type.cyhsu.xyz/2022/08/arc/](https://type.cyhsu.xyz/2022/08/arc/)
- **Vivaldi官网**：[https://vivaldi.com](https://vivaldi.com/)
- **Vivaldi论坛，Modding Vivaldi：**[https://forum.vivaldi.net/topic/10549/modding-vivaldi](https://forum.vivaldi.net/topic/10549/modding-vivaldi)