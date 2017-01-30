# hexo-newsprint

Hexo 印刷风格主题，这套主题适合于主要为中文、日文内容的网站。

## 配置

推荐使用 `hexo-newsprint`

``` Shell
npm un hexo-renderer-marked --save
npm i hexo-renderer-markdown-it --save
npm i hexo-footnotes --save
```

推荐配置 `_config.yaml`（是 hexo 配置不是 theme 的配置）

``` yaml
# Extensions
## Plugins: https://hexo.io/plugins/
plugins: hexo-footnotes

# Markdown-it config
## Docs: https://github.com/celsomiranda/hexo-renderer-markdown-it/wiki
markdown:
  render:
    html: true
    linkify: true
```

## 第三方引用参考

* [han.css](https://github.com/ethantw/Han)
* [manga-image](https://github.com/moeoverflow/manga-image)
* [font-awesome](https://github.com/FortAwesome/Font-Awesome)
* [hexo-footnotes](https://github.com/LouisBarranqueiro/hexo-footnotes)

