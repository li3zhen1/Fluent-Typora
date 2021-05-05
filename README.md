![fluent](/fluent/fluent.png)

# Fluent-Typora

This is a theme carefully crafted & designed for modern computer screens, inspired by [Microsoft Fluent Design System](https://developer.microsoft.com/en-us/fluentui#/).

The theme now has a **built-in** dark mode support. Which means the theme changes with your system, and you don't have to manually setup any preferences.

Separated themes (fluent-light.css, fluent-dark.css) are also provided.

This theme is currently tested on MacOS only.



## ⚠ Installation

The required font faces are not provided in this repository. You should download the font families manually. Otherwise Typora will render by your system's default.

- [Inter](https://github.com/rsms/inter/)
- [Jetbrains Mono](https://www.jetbrains.com/lp/mono/)


- **(If you need Chinese support 如果你需要中文支持)**  Source Han Sans / 思源黑体 
    - Notice that if you have the newly released variable font version of Source Han Sans installed, the typography in your PDF exportation might be corrupted. Modify the variable `--cjk-font` defined in `fluent.css` to fix this. (Strokes in Source Han Sans VF are separated) 
    - 如果你安装了新的可变字体版本思源黑体，PDF 导出可能会出现问题。此时请修改 `fluent.css` 中的 `--cjk-font`。



## Escapings

You can place headers in `blockquote` with extra styles. 

```markdown
> # Bookmark
> This is `H1` inside a block quote.
```

And this theme renders them like this: 

![fluent escaping](/fluent/escaping.png)



## Screenshots

![fluent light](/fluent/fluent-light.png)

![fluent dark](/fluent/fluent-dark.png)