## Todo-tree config
settings.json
```
"todo-tree.tree.showScanModeButton": false,
    "todo-tree.filtering.excludeGlobs": [
        "**/node_modules",
        "*.xml",
        "*.XML"
    ],
    "todo-tree.filtering.ignoreGitSubmodules": true,
    "todohighlight.keywords": [],
    "todo-tree.tree.showCountsInTree": true,
    "todohighlight.keywordsPattern": "TODO:|FIXME:|NOTE:|\\(([^)]+)\\)",
    "todohighlight.defaultStyle": {},
    "todohighlight.isEnable": false,
    "todo-tree.highlights.customHighlight": {
        "BUG": {
            "icon": "bug",
            "foreground": "#F56C6C",
            "type": "text"
        },
        "FIXME": {
            "icon": "flame",
            "foreground": "#FF9800",
            "type": "tag-and-comment"
        },
        "TODO": {
            "foreground": "#FFA500",
            "type": "line"
        },
        "NOTE": {
            "icon": "note",
            "foreground": "#67C23A",
            "type": "whole-line"
        },
        "INFO": {
            "icon": "info",
            "foreground": "#909399",
            "type": "text-and-comment"
        },
        "TAG": {
            "icon": "tag",
            "foreground": "#409EFF",
            "type": "line"
        },
        "HACK": {
            "icon": "versions",
            "foreground": "#E040FB",
            "type": "line"
        },
        "XXX": {
            "icon": "unverified",
            "foreground": "#E91E63",
            "type": "line"
        }
    },
    "todo-tree.general.tags": [
        "BUG",  // 有bug
        "HACK", // 不确定标记
        "FIXME",//
        "TODO", // 待办事项
        "INFO", // 信息
        "NOTE", // 笔记
        "TAG",  // 标签
        "XXX"   // 暂存
    ],
    "todo-tree.general.statusBar": "total",
```