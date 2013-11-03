# 简色系列主题

## 缘起

作者的桌面环境是 Xfce4. 经过长时间使用之后, xfwm4 自带的 (稍微能看的) 主题都看腻了,
至于其他的主题基本上不是风格过于复古, 就是标题栏太矮, 边框太难看...
作者经过长时间的忍受之后, 终于忍无可忍, Google 了 xfwm4 主题自定义方法,
发现居然不用写程序! 于是作者果断打开了他的 Gimp...


## 主题列表

目前只有 Xfce4 的窗口装饰, 更多主题将慢慢推出.
因为作者比较忙, 所以不要对更新频率抱有过高期待 :-P

### xfwm4 主题

* Simplecolor-GaojiBlack (简色-高级黑)


## 安装方法

第一步当然是 `git clone` 下整个版本库 (当然也可以只下载压缩包啦),
然后符号链接或者复制你想安装的主题的目录. 下面是示例命令:

```sh
# 如果只想装到自己用户的话:
cd ~/.themes

# 请自行替换成你克隆的版本库路径
ln -s ../repos/simplecolor-themes/主题名 .


# 如果想装到全系统:
sudo -s
cd /usr/share/themes
ln -s /home/xxx/repos/simplecolor-themes/主题名 .
```

这样再打开你的外观/窗口管理器设置, 应该就能看到你链接进来的主题了.


## 参与设计

任何设计方面的改进或者建议都可以提出, 请将它们提交成项目的 issue.

关于文件格式, 推荐为源文件使用 XCF (Gimp) 或者 SVG (Inkscape) 格式,
因为这是作者主要使用的格式. 其他的格式, 尤其是一些 Adobe 产品的专有格式,
很可能在作者的 Linux 环境存在兼容性问题, 因此最好不要用.


## 授权

<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/"><img alt="Creative Commons License" src="http://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a>

This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/">Creative Commons Attribution-ShareAlike 3.0 Unported License</a>.
本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/deed.zh">知识共享署名-相同方式共享 3.0 未本地化版本许可协议</a>进行许可。


<!-- vim:set ai et ts=4 sw=4 sts=4 fenc=utf-8: -->
