# Create Model

![](https://github.com/worcdlo/BackendFramework/blob/master/django_workflow.png)

- manage.py： 用來操作整個Django專案的小工具
    - 啟動伺服器： python manage.py runserver
    - 同步資料庫： python manage.py syncdb
    - 關聯db並生成django形式的model： python manage.py inspectdb > models.py
    - 將model的異動改到資料庫： python manage.py makemigrations
    
- settings.py： 設定檔

- urls.py： 負責網站的路由
