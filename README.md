<!--
 * @?: *********************************************************************
 * @Author: Weidows
 * @Date: 2021-05-14 04:28:22
 * @LastEditors: Weidows
 * @LastEditTime: 2021-09-29 00:48:02
 * @FilePath: \weidows-beautify-pack\README.md
 * @Description:
 * @!: *********************************************************************
-->

<h1 align="center">

😍weidows-beautify-pack

</h1>

[github-shield]: https://img.shields.io/github/stars/Weidows-projects/weidows-beautify-pack?style=social
[github-url]: https://github.com/Weidows-projects/weidows-beautify-pack

[vscode-shield]: https://img.shields.io/visual-studio-marketplace/r/Weidows.weidows-beautify-pack?logo=visual-studio-code&style=social
[vscode-url]: https://marketplace.visualstudio.com/items?itemName=Weidows.weidows-beautify-pack

[![Github Repo][github-shield]][github-url]
[![VSCode Plugin][vscode-shield]][vscode-url]

> ##  VScode 整合美化包
> ## For more information, [Click here][github-url]

---

# 样式

![](https://cdn.jsdelivr.net/gh/Weidows-projects/weidows-beautify-pack/images/1.png)
![](https://cdn.jsdelivr.net/gh/Weidows-projects/weidows-beautify-pack/images/2.png)


![分割线](https://www.helloimg.com/images/2022/07/01/ZM0SoX.png)


# 应用美化

1. 在 VScode 配置文件中添加下面配置:

  ```json
  // 启用主题 Enable the theme
  "workbench.colorTheme": "Weidows",
  // 引入CSS美化 Inject of CSS beautification
  "vscode_custom_css.imports": [
    "https://cdn.jsdelivr.net/gh/Weidows-projects/weidows-beautify-pack/css/lights-on.css"
  ],
  // 窗口透明度调节 Transparent window
  "glassit.alpha": 220,
  ```

---

2. 按 <kbd>Ctrl + Shift + P</kbd> 执行 `Enable custom CSS and JS` 命令.


![分割线](https://www.helloimg.com/images/2022/07/01/ZM0SoX.png)

# 引用项目

> [pcwalton/vscode-powerline](https://github.com/pcwalton/vscode-powerline)
