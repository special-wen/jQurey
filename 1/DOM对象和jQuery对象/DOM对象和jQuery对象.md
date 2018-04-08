## DOM对象
### 可以通过JavaScript中的`getElementByTagName` 或者 `getElementById`来获取元素节点

## jQuery对象
### jQuery对象是通过jQuery包装DOM对象后产生的对象

- DOM对象不能使用jQuery对象的任何方法
- jQuery对象不能使用DOM对象的任何方法

## jQuery对象和DOM对象的相互转化
- 如果获取的是jQuery对象，则需要在变量名之前加上`$`

## jQuery对象专程DOM对象
1. jQuery对象是一个类似数组的对象，可以通过`[index]`方法得到相应的DOM对象
