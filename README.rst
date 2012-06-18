This app does all the groundwork needed to get an app up and running..
Usage:

Include django-groundwork and the newly created app in your list of installed apps.
Create the models.py file for your app with all the fields specified.

Run the following command

$ manage.py groundwork appname ModelName1 ModelName2

~~~~~~~
Change
~~~~~~~

In django1.4,settings.py and urls.py are all in the folder which has the same name 
with project name,i modified the groundwork.py to place those two files in the right
place.User also can choose whether replace the template_dir or not.

django1.4中，settings.py和urls.py都保存在和项目名称相同的文件夹下，我修改了groundwork.py
使django的位置正确。同时让用户选择是否修改settings.py中的template_dir变量.

~~~~~~~
License
~~~~~~~
django-groundwork is License under the terms of BSD License. Please read the
contents of the LICENSE file in the root of the source repository for the
terms of the license.

~~~~~~~
Authors
~~~~~~~
The authors and/or contributors of django-groundwork is listed in the AUTHORS
file in the root of the source repository.
