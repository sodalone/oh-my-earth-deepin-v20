# oh-my-earth for deepin v20

### 本人在[原版oh-my-earth](https://github.com/ujnzxw/oh-my-earth)的基础上添加了兼容deepin v20的代码。
### 谢谢原版大佬的奉献！
### 仅供娱乐，侵权即删！

主要修改部分为以下：
1. manage_earth.py 原代码网址问题，http->https
2. manage_earth.py ssl认证问题
3. config.py 新增关于deepin壁纸更换的参数
4. 修改utils.py中的set_background()函数，新增deepin选项
5. 修改manager_earth.py中的urllib2
### 注意：该代码只针对earth壁纸，有关momentum壁纸部分未变动

### 壁纸展示如下
![erath](./picture/earth-1.png)

加入crontab的定时任务中，就可以使桌面不断变化成当前拍摄的地球画面
