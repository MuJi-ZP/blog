#### computed vs watch
- 自动生成 data内的一个属性, 有 get / set 方法, 其中 get 方法是获取属性的值, set 方法根据其他属性值 计算 出来的结果赋值
- `watch`: 无缓存性,页面重新渲染时值不变也会执行, 当一个属性影响多个属性的时候, 使用 `watch`
- `computed`: 有缓存性,页面重新渲染时值不变则不会执行, 当一个属性受一个或多个属性影响的时候使用`computed` [计算完整度,百分比,是否可提交表单,是否显示]