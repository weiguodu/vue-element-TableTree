# tree

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

## 注意事项
##### 引入此组件后,为子组件。父组件接收数据后传给子组件,展示列表树状结构。
##### 父组件传递给子组件数据不变，所以一些数据操作需要子组件先绑定事件，再通过$emit传给父组件。父组件再通过v-on绑定传过来的数据，再进行操作。




For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
