#### 在自定义CSS中插入即可

- jsdelivr CDN

```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/urkbio/my-fonts@latest/fonts.css" />
<style>
  body {    
    /* TC version */
    font-family: "LXGW WenKai TC", sans-serif;
  }
</style>
```

现在我把字体和CSS文件放在Cloudflare R2，应该可以快些。

```
<link rel="stylesheet" href="https://media.joomaen.top/fonts.css" />
<style>
  body {    
    /* TC version */
    font-family: "LXGW WenKai TC", sans-serif;
  }
</style>
```

