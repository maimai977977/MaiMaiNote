# 关于静态文档框架选择
## vuepress 
### 关于`vuepress`
VuePress 由两部分组成：第一部分是一个极简静态网站生成器 (opens new window)，它包含由 Vue 驱动的主题系统和插件 API，另一个部分是为书写技术文档而优化的默认主题，它的诞生初衷是为了支持 Vue 及其子项目的文档需求。
官方网站[VuePress](https://vuepress.vuejs.org/zh/)

每一个由 VuePress 生成的页面都带有预渲染好的 HTML，也因此具有非常好的加载性能和搜索引擎优化（SEO）。同时，一旦页面被加载，Vue 将接管这些静态内容，并将其转换成一个完整的单页应用（SPA），其他的页面则会只在用户浏览到的时候才按需加载。
[demo](https://note.maimaio.cn/#/)
### 关于`docsify`
docsify是一个神奇的文档网站生成器。他可以快速帮你生成文档网站。不同于GitBook、Hexo的地方是它不会生成静态的.html文件，所有转换工作都是在运行时。如果你想要开始使用他，只需要创建一个index.html就可以开始编写文档并直接部署在GitHub Pages（码云Pages、阿某云OSS或者鹅云COS等等）
官方网站[Docsify](https://docsify.js.org/#/)
### 个人理解
相对于文档网站个人更偏爱docsify，相对于vuepress，配置和部署都比较方便，便捷
渲染出来的页面也比较的钟爱
> 文档网站 Github+Git+Docsify




