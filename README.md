## A Command Line App For Searching Tickets From 12306

**命令行查询12306的火车票**

![](https://dn-laravist.qbox.me/2015-12-15_20-58-16.png)

## 使用方法:

```
git clone https://github.com/JellyBool/12306.git

cd 12306

composer install

./search 12306 成都 南宁 2016-01-28
```

> 如果你没有安装composer,可以`curl -sS https://getcomposer.org/installer | php` ,
> 或者直接到composer官网 [https://getcomposer.org/download/](https://getcomposer.org/download/)

## 说明:
1.日期为可选参数,如果不传入,默认为查询当天
```
./search 12306 成都 南宁
```

**2. 目前为第一个测试版,后续后慢慢改善**



