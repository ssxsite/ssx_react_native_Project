#### 总结

#### 使用到的Library
* [react-navigation](https://reactnavigation.org)
```
$ npm install --save react-navigation
```
* [react-native-easy-toast](https://github.com/crazycodeboy/react-native-easy-toast)
```
$ npm install react-native-easy-toast --save
```
#### 遇到的问题：

* TabNavigator嵌套TabNavigator：

```
//第二个TabNavigator需要设置如下属性
//参考Main.js中的代码
animationEnabled: false,

swipeEnabled: false,
```
* [解决React Native中使用TabNavigator时、对tab只设置文字时文字没有垂直居中](http://blog.csdn.net/a_zhon/article/details/78432619)

//启动项目
1.npm install （安装依赖）
2.react-native run-android/run-ios (运行项目)

//learn文件夹主要是是学习过程中的的一些demo代码，可以用于后期查询使用




