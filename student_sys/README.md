## LearnDjango

记录下学习Django框架写下的一些代码记录,Django版本为2.0，Python版本3.6.

## 如何运行
### 安装Django
使用pip，推荐使用conda。
```
conda create -n django python=3.6
activate django
pip install Django==2.0
```
以student为例
```
git clone git@github.com:Lt-grint/LearnDjango.git
cd LearnDjango/student_sys
pip install -r requirements.txt
python manager.py migrate # 成功数据库文件，默认是sqllite3
python manager.py createsuperuser # django admin 创建用户 
python manager.py runserver   # 启动web服务
```