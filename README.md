## 演示效果图

### 01
![images](https://github.com/pantone44/DOM-in-30-days/blob/master/imgs/01.gif)

**知识点：**
+ document.getElementById()
+ document.getElementsByTagName()
+ onclick

### 02
![images](https://github.com/pantone44/DOM-in-30-days/blob/master/imgs/02.gif)

**知识点**
+ onmouseover
+ onmouseout

#### DOM(文档对象模型)

+ 文档（Document）：HTML 文件
+ 节点（Node）：文档中的所有内容都可称为节点
    - 标签节点
    - 文本节点
    - 注释节点
    - 属性节点
    - ...
+ 元素（Element）：文档中的标签可以称为元素

#### DOM 可以做什么

+ 找对象
+ 设置对象的属性
+ 设置对象的样式
+ 动态创建元素

#### 事件三要素

+ 事件源
+ 事件
+ 事件处理程序

```
事件源.事件 = function () {
    事件处理程序
}

// 也就是给对象注册一个方法，事件发生时，浏览器去调用这个方法。
```

#### Core DOM

##### Document Methods
+ [getElementById()](https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementById)

+ [getElementsByTagName()](https://developer.mozilla.org/en-US/docs/Web/API/document/getElementsByTagName)
