## 集成 markdown

## 项目描述
1. 下载[editor.md](https://github.com/pandao/editor.md)源码，存放精简后的代码
2. 支持图片上传, 核心点就是我们采用ajax方法直接上传，然后获取返回值，进行赋值，
   修改文件 editormd/plugins/image-dialog/image-dialog.js中的uploadIframe.onload函数
