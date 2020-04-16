# PD-resurrection
感谢@TkzcM 与 @xjxaixxy 大佬提供思路与源文件

https://www.hostloc.com/thread-675311-1-1.html

https://github.com/TkzcM/pandownload-fake-server

## 这个能干啥？

这个可以用来复活你的Pandownload（尽管可能是暂时的）
比起上述的方法，使用这个可以恢复Pandownload的登录功能。

## 使用方法

1. 将 fake-server 中的文件上传到您自己的WEB服务器（注：需要独立IP）
2. 修改HOST文件
### Windows下：

```
C:\Windows\System32\drivers\etc\hosts
```

请使用带有管理员权限的文本编辑器添加如下之内容

```
(您WEB服务器的IP) pandownload.com
```

### GNU/Linux

请使用您喜欢的编辑器修改如下文件

```
/etc/hosts
```

使用带有root权限的编辑器打开上述文件

```
sudo vim /etc/hosts
```

或者是

```
sudo gedit /etc/hosts
```

添加如下内容：

```
(您WEB服务器的IP) pandownload.com
```

### Android
host文件位于：

```
/system/etc/hosts
```

后添加如下内容

```
(您WEB服务器的IP) pandownload.com
```

3. 目前看一切运转正常。

**FUCK BAIDU**
