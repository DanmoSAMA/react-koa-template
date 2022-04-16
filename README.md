# react-koa-template

## 技术栈

前端：react + ts + scss

后端：koa + mongoose

## feat

- 整合了 svg-sprite，使用 icon 时，只需将.svg 放在 /fe/public/assets 下，在.tsx 文件中，引入 SvgIcon 组件，将.svg 的名称作为 name 属性传入即可，如果不了解 svg-sprite，可以参考[svg-sprite](https://milestone.danmoits.com/post?id=625145fd6fedb2487700b666)
- 使用 react-router 配置了前端路由，上手可直接进行开发
- 进行了别名配置，不论在哪个位置，访问项目的根目录只需 @/

## 不足

- 没有配置 eslint + husky + lint-staged

## 参考

[Vite + React + Typescript 最佳实践](https://segmentfault.com/a/1190000039875183)
