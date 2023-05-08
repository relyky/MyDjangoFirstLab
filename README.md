# My Django website first lab
* Django 網站試作。
* 因為它是用 Python 程式語言實作的網站。
* 為了評估是否引用此技術。

# 開發環境組織重點
1. 安裝 [Python](https://www.python.org/)，   
成功後 [pip](https://pypi.org/project/pip/) 工具程式也會順便安裝。
2. 用 `pip` 工具安裝 [Django](https://www.djangoproject.com/)。   
成功後 `django-admin` 也會順便安裝。

# 參考文件
* [Writing your first Django app, part 1](https://docs.djangoproject.com/en/4.2/intro/tutorial01/)

# 開發時下達指令主要過程
---------------
```
/// 確認需要的模組/工具已安裝
PS C:\MyDjangoFirstLab> python --version
Python 3.11.3
PS C:\MyDjangoFirstLab> python -m django --version
4.2.1
PS C:\MyDjangoFirstLab> django-admin --version
4.2.1

/// 下指令建立 Django project。
PS C:\MyDjangoFirstLab> django-admin startproject mysite
PS C:\MyDjangoFirstLab> cd mysite

/// 可立刻啟動網站。
PS C:\MyDjangoFirstLab\mysite> python manage.py runserver

/// 下指令建立 Django app。
PS C:\MyDjangoFirstLab\mysite> python manage.py startapp polls

/// 依 Django 框架樣板改寫程式。加入新網頁新功能等等。
[...]

/// 完成後啟動網站。
PS C:\MyDjangoFirstLab\mysite> python manage.py runserver
```
---------------
# 結論
* 可以快速做出堪用的網站。介面非常的堪用。
* 不適合給終端客戶使用。
* 用起來的感覺跟傳說中的 Ruby on Rails 的體驗差不多。

# 沒圖沒真象
### 初始 Django 網站(看到它就代表成功了)
![初始 Django 網站](/doc/圖片%20001.png)

### 我的第一個 Django 網頁
![我的第一個 Django 網頁](/doc/圖片%20002.png)
