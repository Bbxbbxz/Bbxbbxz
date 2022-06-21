<template><div><h1 id="hello-vuepress" tabindex="-1"><a class="header-anchor" href="#hello-vuepress" aria-hidden="true">#</a> Hello VuePress</h1>
<p><RouterLink to="/">Home</RouterLink> <!-- 跳转到根部的 README.md -->
<RouterLink to="/foo/">foo</RouterLink> <!-- 跳转到 foo 文件夹的 index.html -->
<RouterLink to="/foo/#heading">foo heading anchor</RouterLink> <!-- 跳转到 foo/index.html 的特定 anchor 位置 -->
<RouterLink to="/foo/one.html">foo - one</RouterLink> <!-- 具体文件可以使用 .html 结尾 -->
<RouterLink to="/foo/two.html">foo - two</RouterLink> <!-- 也可以用 .md --></p>
<p>🎉 💯 阿斌的文档</p>
</div></template>
