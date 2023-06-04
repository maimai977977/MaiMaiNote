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
-介绍
    -[介绍](zh-cn/mai)
    -[关于](zh-cn/note/vuepress-Or-docsify.md)
    -[hexo](zh-cn/note/hexo-快速、简洁且高效的博客框架.md)
    -[MyNav](zh-cn/note/MyNav.md)
    -[感冒互换魔法](zh-cn/note/16.%E6%84%9F%E5%86%92%E4%BA%92%E6%8D%A2%E9%AD%94%E6%B3%95.md)
    -[html转md](zh-cn/note/html%E8%BD%ACmd.md)
    -[工具](zh-cn/note/%E5%B7%A5%E5%85%B7.md)
    -[img测试](zh-cn/note/img%E6%B5%8B%E8%AF%95.md)

-书单分享
    -[为什么精英都是时间控](zh-cn/books/1.%E4%B8%BA%E4%BB%80%E4%B9%88%E7%B2%BE%E8%8B%B1%E9%83%BD%E6%98%AF%E6%97%B6%E9%97%B4%E6%8E%A7.md)
    -[我的职业是小说家](zh-cn/books/2.%E6%88%91%E7%9A%84%E8%81%8C%E4%B8%9A%E6%98%AF%E5%B0%8F%E8%AF%B4%E5%AE%B6.md)
