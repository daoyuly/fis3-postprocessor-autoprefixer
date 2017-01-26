# fis3-postprocessor-autoprefixer
基于[postcss/autoprefixer](https://github.com/postcss/autoprefixer)的fis3插件，用于css的兼容性前缀的自动添加


## install

`cnpm install fis3-postprocessor-autoprefixer -g`

## usage 


```
fis.match('/src/(**)/*.css', {
    postprocessor: fis.plugin('autoprefixer')   

    // 配置@see https://github.com/postcss/autoprefixer  https://github.com/ai/browserslist#queries
});

```

