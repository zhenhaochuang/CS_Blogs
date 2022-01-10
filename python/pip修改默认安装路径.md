- 查看是否安装pip

```
pip --version
```

- 使用命令查看pip默认安装目录

```
python -m site
```

- 使用pip查看第三方包的安装路径

```
pip show redis
```

- pip 安装包的时候加上参数--user 包就会自动安装到上面的自定义路径下面

```
pip install redis --user
```

参考：

[PIP INSTALL 默认安装路径修改](https://www.cnblogs.com/yinliang/p/12931685.html)

