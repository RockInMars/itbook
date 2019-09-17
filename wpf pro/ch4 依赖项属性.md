## ch4 依赖项属性

#### 1 理解依赖项属性

##### 1.1 定义依赖项属性

- 根据约定，定义依赖项属性的字段名称是在普通属性的末尾加上“Property”

##### 1.2 注册依赖项属性

- 依赖项属性（DependencyProperty）对象不能被直接实例化，只能使用静态方法DenpendencyProperty.Register()方法创建DenpendencyProperty，该对象为只读对象。

##### 1.3 添加属性包装器

##### 1.4 wpf使用依赖项属性的方式

- 支持两个关键行为--更改通知和动态值识别

##### 1.5 共享的依赖项属性

##### 1.6附加的依赖项属性

#### 2 属性验证

两种属性值验证方式

- validatevaluecallback 接收或拒绝新值
- coercevaluecallback 将新值更改为符合要求的值

##### 2.1 验证回调

validatevaluecallback 注册自定义的验证函数

##### 2.2 强制回调

coercevaluecallback 注册自定义的验证函数