##Create Object
###1.工厂模式
###2.构造函数模式
####创建自定义的构造函数意味着将来可以将它的实例标识为一种特定的类型，constructor属性
###3.原型模式
####创建的实例中的原型指针是与原型对象关系的连接，而不是与构造函数的连接
####每当代码读取某个对象的某个属性时，都会执行一次搜索，先搜索实例对象，然后再搜索原型对象
####设置了实例属性屏蔽了原型对象同名属性后，即使把实例属性设置为null都无法回复只想原型的连接，唯有使用delete删除实例属性，才能使我们重新访问原型中的属性
###4.组合使用构造函数模式和原型模式
###5.动态原型模式
###6.寄生构造函数模式
###7.稳妥构造函数模式