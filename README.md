# 目录操作

目录组件用于对常用目录操作的实现
[TOC]

####创建实例
```
$obj = new \houdunwang\dir\Dir();
```

####创建目录

```
$obj->create('Home/View');
```

####删除目录

```
$obj->del('Home');
```

####复制目录

```
$obj->copy('a','b');
```

####删除文件

```
$obj->delFile($file);
```

####移动目录

```
$obj->move('a','b');
```

####目录树

```
$obj->tree('Home');
```

####目录大小

```
$obj->size('Home');
```

####移动文件
```
$obj->moveFile('hd.php','data');
//将hd.php 移动到data目录
```