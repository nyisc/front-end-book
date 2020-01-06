## 14.3 React代码规范

基本规则

- 每个文件只能包含一个React组件
- 使用JSX语法

命名

文件名
`const ReservationCard = require('./ReservationCard');` 
引用名
`const reservationItem = ;` 
组件命名
使用文件名作为组件名。
`const Footer = require('./Footer')；` 

对齐

当存在两个及以上的属性的时候，每个属性单独占一行

```jsx
<Foo
  superLongParam="bar"
  anotherSuperLongParam="baz"
/>
```

引号

咱们只针对JSX使用双引号，对于其他所有的JS属性使用单引号
`<Foo bar="bar" />` 
`<Foo style={{ left: '20px' }} />` 

空格

在自闭和标签之前留一个空格

属性

属性名采用Camel法

```jsx
<Foo 
  userName="hello"
  phoneNumber={123456}
/>
```

标签

没有子组件的父组件使用自闭和标签
`<Foo className="stuff" />` 

缩进

使用两个空格为一个缩进单位

表达式

表达式中的运算符与操作数之间需要空格