# hexo-newsprint

Hexo 印刷风格主题，这套主题适合于主要为中文、日文内容的网站。

## 配置

推荐使用 `hexo-renderer-markdown-it`

``` Shell
npm un hexo-renderer-marked --save
npm i hexo-renderer-markdown-it --save
npm i markdown-it-footnote --save
```

推荐配置 `_config.yaml`（是 hexo 配置不是 theme 的配置）

``` yaml
# Markdown-it config
## Docs: https://github.com/celsomiranda/hexo-renderer-markdown-it/wiki
markdown:
  render:
    html: true
    linkify: true
  plugins:
    - markdown-it-footnote
```

## 第三方引用参考

* [han.css](https://github.com/ethantw/Han)
* [manga-image](https://github.com/moeoverflow/manga-image)
* [font-awesome](https://github.com/FortAwesome/Font-Awesome)
* [hexo-renderer-markdown-it](https://github.com/celsomiranda/hexo-renderer-markdown-it)

