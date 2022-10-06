提取了Monaco Editor官方的editor.main.nls.zh-cn.js，直接改文件名为editor.main.nls.js但是不行，遂将unicode转中文但还是不行，把第一行中的editor.main.nls.zh-cn改成editor.main.nls后成功

但是并不是最佳处理方法，这种方法不能支持多语言环境（只有中国人能用），正确的方法应该是动态加载。
可以参考https://github.com/chanelnumberseven/monaco-editor-locale等但是并未成功
于是只能取此下策。。

Joe
2022年10月6日