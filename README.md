# dataAnylsis_homework

这是天津大学研究生课程：数据挖掘 `(学堂在线网络课程)` 课后练习

这个文件是通过抓取学堂在线中的`json`文件生成课后题汇总，这仅仅是一个练习而已，没有太多的更加详细具体的内容。


# 生成word文档
通过运行[json2word.py](json2word.py)文件可以生成word文档。

## 需要的Python依赖包
- `re`
- `python-docx`
- `Pillow`
- `json`
- `requests`
- `base64`
- `os`

![生成的word](./image/word.png)



# 生成html在线网页
通过读取json文件，在网页中显示。该文件源码在[dataAnalysis.html](./html/dataAnalysis.html)。

使用浏览器打开[在线预览](https://secoworld.github.io/html/dataAnalysis.html)文件即可访问。

![生成的html文件](./image/html.png)