# 前端代码规范

> 丽晶-1.0-前端开发文档



### 项目目录结构
```
build/ -- 构建目录
config/ -- 构建配置目录
src/ -- 源代码目录（重点关注目录）
  assets/ -- 需要打包的资源目录
  common/ -- 公共服务
    ajax.js -- ajax封装
    eventBus.js -- 事件中心封装
    storage.js -- 存储封装（Local, Session, Memory)
  components/ -- 组件目录（此处用于放置公共组件）
  pages/ -- 页面目录，具体的页面
  App.vue
  main.js -- 程序入口文件
router/ -- 全局路由配置目录
  index.js -- 路由配置文件
static/ -- 第三方静态资源目录
index.html  -- 入口HTML文件
...
```
