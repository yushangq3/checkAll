# checkAll
面试遇到的一些问题

## foreach问题
### foreach()怎么跳出循环
 foreach不会跳出，只能循环完，如果使用跳出 可以用 try catch 
 

## 定义变量，如何确定是array 或者是object

## 匿名函数 匿名立即执行函数

## 浅拷贝 和深拷贝

## 数组去重
## 数组排序

## 大量数据下的性能优化 
  比如 1万+数据



## vue 双向绑定 及 缺点

## vue-router 生命周期

beforeEach 全局前置守卫
router.beforeResolve 注册一个全局守卫
afterEach
beforeEnter
beforeRouteEnter
beforeRouteUpdate
beforeRouteLeave

导航被触发。
在失活的组件里调用离开守卫。
调用全局的 beforeEach 守卫。
在重用的组件里调用 beforeRouteUpdate 守卫 (2.2+)。
在路由配置里调用 beforeEnter。
解析异步路由组件。
在被激活的组件里调用 beforeRouteEnter。
调用全局的 beforeResolve 守卫 (2.5+)。
导航被确认。
调用全局的 afterEach 钩子。
触发 DOM 更新。
用创建好的实例调用 beforeRouteEnter 守卫中传给 next 的回调函数。