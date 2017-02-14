# fileChooser

## 描述

文件选择相关API

## 项目地址

[weex-file-chooser](https://github.com/weex-plugins/weex-file-chooser)

## API
### `chooseFile(acceptType, callback)`
选择文件
#### 参数
- `acceptType {string}`: 限定选择目标文件的类型，需遵循[MIME](http://www.w3school.com.cn/media/media_mimeref.asp)规范
- `callback {function}`: 选择回调
	- `result {string}`: success/cancel
    - `uri {string}`: 文件URI
    - `path {string}`: 文件在磁盘上的真实路径
