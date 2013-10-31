简介
=======

这是百度的开源的一个 [umeditor](http://ueditor.baidu.com/website/)，简称 UM，是 ueditor 的 mini 版本。

本项目的 umeditor 版本为：1.0.0

干的坏事
=======

为适应项目需求，我们只需要编辑区域，为此可以适当删除一些东西。

- 移除默认的 toolbar 所有组件
- 移除 lang

由于其 UI 和其接口是分开的，所以即使移除了 UI 组件，我们仍然可以调用其接口。

故我们可以根据实际的需求，写自己的 UI。

因为其 lang 语言包是跟 toolbar 相关的，所以移除 toolbar 的同时，也可以移除 lang 包。
