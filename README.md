# Time-line
纯 CSS 实现的 时间线，也支持使用 JavaScript 生成。
[DEMO | 演示](https://nowtime.cc/time-line.html)
![Time-line 预览图](https://i.loli.net/2020/01/11/h3AJcmNTKsSiQZF.png)

# HTML 渲染
你只需要根据 `timeLine.html` 代码结构进行简单的修改即可实现

# JacaScript 渲染
你需要将 [timeLine.html](./timeLine.html#L103) `103 行` 取消注释，然后根据 [timeLine.js](./timeLine.js) 注释修改

## timeLine.js 里 `data变量` 数据格式如下：
```
[
  {
    "title":"现在网",
    "link":"https://nowtime.cc",
    "time":"1578718860"
  },
  {
    "title":"ffmpeg 使用方法合集",
    "link":"https://nowtime.cc/software/834.html",
    "time":"1578725484"
  }
]
```
> 字段解释：
>> `title` 时间线显示的内容 

>> `link` 点击后跳转的链接 

>> `time` 该内容发布的时间，注意是 **秒级时间戳** ！

# 鸣谢
> 部分 CSS 样式参考的是 https://www.ihewro.com/archives.html

# LICENSE
[MIT LICENSE](https://github.com/PrintNow/TimeLine/blob/master/LICENSE)
