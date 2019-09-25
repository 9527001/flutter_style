# flutter_style
flutter开发规范
# 命名规范
### 1.  xxx.dart文件建议小写(e.g. address.dart)，如果多单词，使用下划线分割（e.g. address_selector.dart）
### 2.  dart内文件命名方式 
#### 2.1 大驼峰  AdressSeleor
#### 2.2 私有方法前面加上下划线&&大驼峰 e.g. _Address 
#### 2.3 枚举 全部大写或者小写 
~~~ Flutter
/*倒计时状态*/
enum CountDownType {
  START, //初始状态
  LOADING, //等待
  ING, //倒计时中
  END, //倒计时结束，待重新计时
  ERROR,//异常
}
~~~
