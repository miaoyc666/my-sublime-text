# my-sublime-text

#### 插件安装
1. 首先打开Sublime Text，使用快捷键Shift+Ctrl+P，弹出搜索框
2. 在搜索框中直接输入install，出现下拉选项
3. 点击选择其中的Install Package Control，等待安装
4. 安装完成后，Shift+Ctrl+P后输入install，可以看到Package Control：Install Package

#### 一些好用的插件
1. MarkdownEditing：Markdown插件，提供了丰富的语法高亮和主题，以及实时预览功能

#### settings
```json
{
    "font_size": 17,
    "draw_white_space": "all",
    "tab_size": 4, 
    "translate_tabs_to_spaces": true,
    "ignored_packages": [
    ],
    "vintage_start_in_command_mode": true,
}
```

#### key bindings
```json
[
    {"keys": ["ctrl+w"], "command": "delete_word", "args": {"forward": false, "sub_words": true}}
]
```
