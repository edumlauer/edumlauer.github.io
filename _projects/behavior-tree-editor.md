---
title: "Behavior Tree Editor"
excerpt: ""
order: 2
header:
  teaser: assets/images/behavior-tree-editor/bte.png
sidebar:
  - title: "Role"
    text: "Designer, Developer"
  - title: "Platforms"
    text: "Windows, macOS, Linux"
  - title: "Tech"
    text: "Unity"

gallery:
  - url: /assets/images/behavior-tree-editor/bte.png
    image_path: assets/images/behavior-tree-editor/bte.png
---

Behavior tree editor made in Unity with drag-and-drop and automatic tree organization, so you don't have to worry about it. Nodes area loaded dynamically from JSON files. The project is under development and the intention is to eventually make its source available.

This project follows the [MVC Pattern for Unity](https://www.jacksondunstan.com/articles/3092) described by Jackson Dunstan.

Example node:
```json
{
    "name": "randomInt2",
    "color": "9F3A93",
    "description": "Generates a random value between (0, 0) and Max",
    "numberOfChildren": 0,
    "properties": [
        {
            "name": "max",
            "type": "int2"
        },
        {
            "name": "key",
            "type": "string"
        }
    ]
}
```

{% include gallery %}