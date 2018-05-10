---
description: API
---

# API

### [Dialogue](api.md#dialogue)

 对话处理是AVG最常用的功能之一。这部分的接口包括对话框的展示与隐藏、立绘效果处理等。

#### 显示对话

*  显示对话框并展示一段对话文本。

```javascript
    api.showText("少年，你想知道什么呢？", {
        name: "风见",
        character: {
            index: 4,
            avatar: {
                file: "tutorial/girl-normal.png"
            }
        }
    });
```



#### 隐藏对话 {#-2}

* 隐藏对话框

```javascript
 api.hideText()
```

### [Sound](api.md#sound)

 用于控制游戏音频的模块。包括背景音乐、音效、语音的播放与暂停。



