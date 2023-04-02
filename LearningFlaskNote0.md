# Quick Start

在計劃根目錄位置創建根目錄
```
$ mkdir watchlisl
$ cd watchlist
```

創建 Git 倉庫
```
$ git init
Initialized empty Git repository in ~/watchlist/.git/
```

創建忽略規則文檔
```
$ nano .gitignore
```

在 nano 中寫入可忽略的文件規則
```
*.pyc
*~
__pycache__
.DS_Store
```

# 創建虛擬環境

使用 Python 3 内置的 venv 模塊創建
```
$ python -m venv env
```

激活虛擬環境
```
$ . env/Scripts/activate
```

退出虛擬環境
```
(env) $ deactivate
```

# 安裝 Flask

在虛擬環境安裝
```
(env) $ pip install flask
```
