# Viewer.js-inline  
1. 业务的需求需要设计一个内联的图片预览操作模块，主要参考了[Viewer.js](https://github.com/fengyuanchen/viewerjs)，感谢大神，功能非常强大。
2. 主要是对实例代码的custom-toolbar.html进行了修改，根据api改为了inline mode，去除了模态框灰色背景，去除了右上角按钮。
3. 隐藏了背景图片，并且通过定位让底部的工具栏变成了竖的，我觉得横的挺好看的，但需求让改成竖的。
4. 对于一些样式的修改，主要通过css样式的覆盖，而不是直接改动源码，这样方便以后的开发加工。
