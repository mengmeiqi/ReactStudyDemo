# ReactStudyDemo

## React 基础知识

### 1.学习React官方文档
#### ReactJS官网地址: https://reactjs.org/
#### Github: https://github.com/facebook/react
#### ReactJS中文文档: https://react.docschina.org/

### 2.引入

####  1⃣ 引入js文件
##### <script crossorigin src="https://unpkg.com/react@16/umd/react.production.min.js"></script> react核心文件
##### <script crossorigin src="https://unpkg.com/react-dom@16/umd/react-dom.production.min.js"></script>  react-dom 虚拟DOM
##### <script crossorigin src="https://npmcdn.com/babel-core@5.8.38/browser.min.js"></script>  bable（babel 可以转换很多脚本语言）
####  2⃣ 或者使用npm，安装脚手架
#### 引入type=“text/babel”
##### <script type="text/babel"></script>

### 3.ReactDOM.render()

#### ReactDOM.render() 将React元素渲染到DOM节点中

##### `let el = <div>mengmeiqi</div>`
##### `ReactDOM.render(`
#####       `<div>`
#####           `<h1>Header Hello World</h1>`
#####           `{el}`
#####       `</div>,`
#####       `document.getElementById('root')`
##### `);`