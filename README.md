# Type Theme [EasyApple](http://www.easyapple.net) Edition

Type Theme is a free and open-source [Jekyll](http://jekyllrb.com) theme. Great for blogs and easy to customize.

[Using Type](https://rohanchandra.github.io/project/type/)

## EasyApple 修改内容

这一版本EasyApple为适应自身需求及中文环境使用习惯在原版基础上修改的，调整了部分默认格式、字号等，并增加了微博、多说评论等功能的支持。具体修改内容如下：

- 调整默认标题字号，原字号偏大，尤其在手机等设备上略显突兀，本版本将h1/h2/h3字号适当调小。详见：/_sass/base/_global.scss

- 调整默认Header区域字号，原字号较小与此处内容不是很搭故适当改大，可在Demo中体会。详见：/_sass/layouts/_index.scss

- 修改默认Header区域背景颜色，主要是为了与Logo色调统一。详见：/_sass/base/_variables.scss($header-desc-background-color)

- icon区域增加新浪微博，原版只有Google/Facebook/Twitter等，此版本增加本土的新浪微博，效果可在Demo中查看。详见：/_config.yml, /_includes/icons.html

- 修改默认参数开启Post Navigation，并调整导航链接样式，去除标题使其不致过长。详见：/_config.yml, /_layouts/post.html

- 增加多说评论框的支持，原版评论框架为disqus，不够本地化而且后面有一堆乱七八糟的链接，体验非常不好，本版本添加了国内最流行的多说。详见：/_config.yml, /_includes/duoshuo.html



## Demo: [http://i.easyapple.net](http://i.easyapple.net)

## License
The MIT License (MIT)