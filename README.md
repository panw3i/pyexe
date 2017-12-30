### 使用方法

1.  pip install pypiwin32
2.  pip install pyinstaller
3.  打包命令

```
pyinstaller -F -w -i manage.ico app.py
```
4. 参数 
```
-F：打包为单文件
-w：Windows程序，不显示命令行窗口
-i：是程序图标，app.py是你要打包的py文件
```


