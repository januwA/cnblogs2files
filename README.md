## 命令行工具, 将备份的[cnblogs.xml]转为[.md]格式文件，便于保存到有道云笔记

> 通常时文件名含有非法符号/ \ : * ? " < > |  会导致保存失败

## 安装
```sh
$ npm i cnblogs2files -g
```

## 使用
```sh
$ mkdir data && cd data
$ cnblogs2files --xml /data.xml
```