# 网页加载速度调优

## HTTP请求数量太多
- 分类合并同质资源，减少文档中引入的资源数量
- 减少业务逻辑代码中不必要的请求

## HTTP请求返回的结果或资源过大
- 控制结果集
- 压缩处理静态资源

## jS文件放到了document开头

## 使用Base64 编码处理图片，然后嵌到html或css文件里，会很可观的减少http请求

Base64的试用场景
- 图片比较小（10k以内）
- 用法特殊性，不能被制作到雪碧图里
- 站点里复用率高，更新频度低
 

## 小图标合并成sprite图

## 使用浏览器缓存 

## 试用CDN提供静态资源（css,js files）

