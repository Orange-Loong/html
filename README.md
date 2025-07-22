## 一、概述

开发者可以使用熟悉的 Web 技术，如 HTML、CSS 和 JavaScript，来扩展 Editor应用程序。
JS Plugin最基本的形式是一些简单的网页，这些网页在 Eidor程序里显示，但它们不和PDF文件或者互联网上的其他东西交流。
如果你想让这些网页使用网上的资源，可以用任何你喜欢的技术来制作网页，比如 PHP 或 Node.js。
如果想让网页和Editor 程序以及打开的PDF文件进行更深入的交互，你可以使用JS Plugin SDK，它提供了很多功能接口来帮助完成这个任务。

## 二、快速开始

快速部署一个 Javascript Plug-in SDK for Desktop Editor 程序：

我们提供了五个示例项目：Annotation、Document、InsertText、RibbonBar、SearchText

以Annotation为例：
1.设置启动项

<img width="1347" height="274" alt="image" src="https://github.com/user-attachments/assets/b9857638-4f26-4a49-a511-fbf48e47a8d3" />


2.打开Annotation项目下manifest.json清单文件，点击运行后，将CloudStudio测试地址写入Url
<img width="1655" height="650" alt="image" src="https://github.com/user-attachments/assets/180978d1-025e-4a38-a54a-48cc5d3ed8e2" />

3.将manifest.json下载到本地后，通过福昕PDF高级编辑器安装清单文件
<img width="1915" height="768" alt="image" src="https://github.com/user-attachments/assets/4a5c40fa-e091-4d26-af02-fb18bb3f3ab5" />


**输出结果：**

<img title="" src="img/output.png" alt="" width="261">

## 三、文件结构

```
workspace/
├── .vscode 
│   └── preview.yml   // Cloud Studio 配置文件（运行、预览等）
├── Annotation        // 提供对PDF文件中注释进行添加、编辑和删除操作的示例。
├── Document          // 提供对文档的相关操作，获取文档权限，关闭保存文档，翻页，插入、替换页面等。
├── InsertText        // 演示如何在PDF页面中插入文本对象，包括文本定位和格式设置。
├── RibbonBar         // 说明如何在编辑器界面上使用Ribbon按钮进行各种操作的示例。
├── SearchText        // 提供在PDF文件中搜索特定文本并高亮显示结果的操作示例。   
```

## 帮助和支持

##### 欢迎加入Foxit Plugin SDK 用户支持群

当您遇到问题需要处理时，您可以直接通过到扫码进入Foxit Plugin SDK用户群进行提问.

- 福昕工程师实时群内答疑

<img title="" src="img/qr-code.png" alt="qr-code.png" width="270">
