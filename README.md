# Chrome技巧
一、选择器
> 不管有無引入jQuery，都可以通过$(selector)选取元素

二、查找DOM中元素关联的事件
> 可以查看普通绑定事件，对jq等库不奏效。getEventListeners($(‘firstName’)).click[0].listener

三. 查询代码块执行时间
> console.time('myTime'); //Starts the timer with label - myTime
> console.timeEnd('myTime'); //Ends the timer with Label - myTime

四、将数据生成表格

> console.table([{a:1, b:2, c:4}]) 

![image](https://cloud.githubusercontent.com/assets/18028533/25693756/a9b84606-30dd-11e7-8514-72895c8a47c2.png)

五、定位到对应元素
> inspect($('selector')) 

六、选中之前检查过的元素
> $0    $1     $2.......

七、列举出元素所有属性

> dir($('selector')) 

八、获取最近一个结果值

> $_

九、清空控制台和内存
> clear()

十、带格式的输出
```js
console.group("%c ws通讯消息","color:#296ab4;");
console.log(112233);
console.end();
```
## [JavaScript issue目录](https://github.com/Kelichao/JavaScript/issues)
javascript
js的相关基础知识要点
- [43.【重排，重绘】要点](https://github.com/Kelichao/javascript.basics/issues/43)
- [42.【while,for】两大循环相互之间的联系与优缺点](https://github.com/Kelichao/javascript.basics/issues/42)
- [41.【前端安全】JavaScript防http劫持与XSS](https://github.com/Kelichao/javascript.basics/issues/41)
- [40.【hash路由】注意点](https://github.com/Kelichao/javascript.basics/issues/40)
- [39.【逗号】操作符](https://github.com/Kelichao/javascript.basics/issues/39)
- [38.【函数声明】，函数表达式，区分与理解](https://github.com/Kelichao/javascript.basics/issues/38)
- [37.【new Date()】日期方法](https://github.com/Kelichao/javascript.basics/issues/37)
- [36.【字面量对象】初始化中的问题](https://github.com/Kelichao/javascript.basics/issues/36)
- [35.【动态脚本】的加载](https://github.com/Kelichao/javascript.basics/issues/35)
- [34.【number】类型处理手段](https://github.com/Kelichao/javascript.basics/issues/34)
- [33.【undefined】被重写问题](https://github.com/Kelichao/javascript.basics/issues/33)
- [32.【if判断语句】规律](https://github.com/Kelichao/javascript.basics/issues/32)
- [31.【编码，解码】方式总结](https://github.com/Kelichao/javascript.basics/issues/31)
- [30.【对象类型】的判断](https://github.com/Kelichao/javascript.basics/issues/30)
- [29.【抽象类】Widget-继承](https://github.com/Kelichao/javascript.basics/issues/29)
- [28.【http请求头】、请求工程](https://github.com/Kelichao/javascript.basics/issues/28)
- [27.【递归】执行过程](https://github.com/Kelichao/javascript.basics/issues/27)
- [26.【AMD / CMD】规则 ](https://github.com/Kelichao/javascript.basics/issues/26)
- [25.【变量未定义】、变量未初始化](https://github.com/Kelichao/javascript.basics/issues/25)
- [24.【DOM】操作](https://github.com/Kelichao/javascript.basics/issues/24)
- [23.【iframe】嵌套，以及调用的规则。](https://github.com/Kelichao/javascript.basics/issues/23)
- [22.【发布/订阅模式、观察者模式】JS设计模式](https://github.com/Kelichao/javascript.basics/issues/22)
- [21.【安全】构造函数法](https://github.com/Kelichao/javascript.basics/issues/21)
- [20.【伪数组】、类数组 对象介绍以及区别](https://github.com/Kelichao/javascript.basics/issues/20)
- [19.【小括号】的用法总结（自执行函数）](https://github.com/Kelichao/javascript.basics/issues/19)
- [18.【改变this指向】通过间接引用，意外改变this指向案例](https://github.com/Kelichao/javascript.basics/issues/18)
- [17.【继承】在Javascript中](https://github.com/Kelichao/javascript.basics/issues/17)
- [16.【克隆】浅复制与深复制](https://github.com/Kelichao/javascript.basics/issues/16)
- [15.【原型链】关系的方法汇总](https://github.com/Kelichao/javascript.basics/issues/15)
- [14.【代码执行顺序】的相关要点，以及对值的影响](https://github.com/Kelichao/javascript.basics/issues/14)
- [13.【面向对象】的编程方式总结。](https://github.com/Kelichao/javascript.basics/issues/13)
- [12.【迭代】for循环，forEach，map，$.each()，some，fliter，every区别与联系](https://github.com/Kelichao/javascript.basics/issues/12)
- [11.【定时器】相关的注意点](https://github.com/Kelichao/javascript.basics/issues/11)
- [10.【offsetHeight】offsetHeight,offsetTop:clientHeight;clientTop 区别](https://github.com/Kelichao/javascript.basics/issues/10)
- [9.【dom节点操作】原生方法操作属性值，以及操作方式](https://github.com/Kelichao/javascript.basics/issues/9)
- [8.【数组】Array常用方法总结](https://github.com/Kelichao/javascript.basics/issues/8)
- [7.【字符串】String常用方法总结](https://github.com/Kelichao/javascript.basics/issues/7)
- [6.【call， apply，bind，$.proxy()】改变this指向的途径 ](https://github.com/Kelichao/javascript.basics/issues/6)
- [5.【冒泡，二分法】数组常用排序方法](https://github.com/Kelichao/javascript.basics/issues/5)
- [4.【闭包】JavaScript](https://github.com/Kelichao/javascript.basics/issues/4)
- [3.【滚动条】scrollTop,scrollHeight](https://github.com/Kelichao/javascript.basics/issues/3)
- [2.【prototype，this】JS面向对象总结（笔记）](https://github.com/Kelichao/javascript.basics/issues/2)
- [1.【文档加载完毕】检测浏览器](https://github.com/Kelichao/javascript.basics/issues/1)

