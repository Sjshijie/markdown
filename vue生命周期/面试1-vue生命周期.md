## vue生命周期

1、beforeCreate（组建创建前）<br>
这是内部开始定义vue的各个属性，比如data，method等，但还没有具体的值，且dom对象也没有生成。<br>
2、created（创建后）<br>
这时vue开始给data等属性赋值了，但是dom对象还是没有生成<br>
3、beforeMounted（挂载前）<br>
data有值，生成dom对象，但此时还是虚拟dom，{{message}}<br>
4、mounted（挂载后）<br>
开始渲染页面<br>
5、beforeUpdate（更新前）<br>
改变data，在修改data里的属性前触发
6、update(更新后)<br>
改变data，在修改data里的属性后触发
7、beforeDestory（销毁前）<br>
8、destoryed（销毁后）
