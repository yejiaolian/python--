# python--
记录python—django 错误及解决方法

（1）django 安装失败，可用以下形式下载即可。
解决方法：运行 pip install -i https://pypi.douban.com/simple django

（2）在使用admin后台管理，添加或者修改数据库时，出现错误，no such table: main.auth_user__old。
解决方法：更新django至2.2版本以上，django升到2.7版本,把原来的数据库删除,再重新运行,重新生成数据库。

（3）在命令里显示没有pip
解决方法：   python setup.py install
