# 局域网访问Jupyter Notebook的设置方法

## 1.安装Jupyter Notebook
```pip install jupyter```

## 2.导出Jupyter Notebook的配置文件
```
jupyter notebook --generate-config
```


## 3.对Jupyter Notebook的配置文件做如下修改

```python
c.NotebookApp.ip='*'

c.NotebookApp.open_browser = False

c.NotebookApp.port =8888
```

## 4.启动Jupyter Notebook

```
jupyter notebook  --ip=0.0.0.0 --no-browser --allow-root
```

然后根据命令行提示的URL登录即可






