# 嵌套的侧边栏
你可能想要浏览到一个目录时，只显示这个目录自己的侧边栏，这可以通过在每个文件夹中添加一个 _sidebar.md 文件来实现。

_sidebar.md 的加载逻辑是从每层目录下获取文件，如果当前目录不存在该文件则回退到上一级目录。例如当前路径为 /zh-cn/more-pages 则从 /zh-cn/_sidebar.md 获取文件，如果不存在则从 /_sidebar.md 获取。

当然你也可以配置 alias 避免不必要的回退过程。
```
<script>
  window.$docsify = {
    loadSidebar: true,
    alias: {
      '/.*/_sidebar.md': '/_sidebar.md'
    }
  }
</script>
```
<!-- docs/_sidebar.md -->
<!-- 定制侧边栏 -->
