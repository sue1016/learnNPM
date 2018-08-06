# README  
how i learned npm


------  

## 简介  

npm是nodejs的一个模块。  
通过这个模块，  
我们可以从npm的网站上面  
下载js模块，  
上传js模块。  
从npm网站上下载下来的js模块可以直接应用到我们的项目之中。  
大大提高我们的工作效率。  

首先要正确安装nodejs。  
假定已经安装。 

------  

## 安装包  

eg: 
npm i jquery 在当前目录下局部安装jquery
npm -g i jquery 全局安装jquery  

* [npm 安装出现 UNMET DEPENDENCY 的解决方案][1]  
* [mac下nodejs 更新到最新版本的最新方法][2]  
* [npm install模块时 报错：not such file or directory][3]  
* [nodejs中的npm全局安装和局部安装的意思，npm中的全局安装和局部安装的区别][4]     
* [npm won't install packages locally. What's wrong?][5]  

[1]:https://lellansin.wordpress.com/2014/02/27/npm-%E5%AE%89%E8%A3%85%E5%87%BA%E7%8E%B0-unmet-dependency-%E7%9A%84%E8%A7%A3%E5%86%B3%E6%96%B9%E6%A1%88/  
[2]:https://blog.csdn.net/chwshuang/article/details/54965100  
[3]:https://segmentfault.com/q/1010000012930521 

[4]:https://blog.csdn.net/jiang7701037/article/details/80706920

[5]:https://blog.csdn.net/davidsu33/article/details/52633904

------

## 卸载包  

在所在目录下  
npm uninstall jquery 卸载当前目录下的jquery  

------  

## 生成配置文件  

一次性想从npm网站上下载多个模块  
可以一条一条输入  
也可写在相应的配置文件里  g

npm init  

-------  

## 使用配置文件  

eg:  
npm i lodash  

然后查看配置文件  

如果想下载指定版本     
npm i lodash@4.17.5    

再次查看配置文件  
版本已变   

如果只有一个配置文件，但是还没有下载模块，只需要在有配置文件的目录里，  
npm i   
就会自动下载配置文件里的模块  

比如你可以试试删除刚刚下载的模块  
这个时候配置文件里仍有刚刚删除的模块，  
npm i  
又会重新下载该模块  






