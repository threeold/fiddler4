# fiddler 使用

#### 域名替换 方式一
urlreplace  www.baidu.com  www.sina.com



#### 域名替换 方式二 
AutoResponder 拦截重定向  add rule

regex:http://www.baidu.com/(.*)
http://www.sina.com/$1


