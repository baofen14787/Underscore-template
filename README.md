#Underscore template

将大名鼎鼎的Underscore 里面的的template 单独抽出来使用。

Underscore 版本为 1.6.0

###如何选择模板引擎

模板引擎的原理很简单，无非是正则对字符串的替换。但是光模板引擎这块就有非常多著名的temlpate，如mustache.js , 比mustache更快，功能更全的Handlebars.js。还有目前我在用的这个Underscore template。另外还有jQuery之父John 的micoro template.js。


如何选择是个问题。这里推荐一个网站，感觉不错。http://garann.github.io/template-chooser/

里面列了7个问题，简单的翻译一下：

1. 模板需要在客户端使用还是服务器端？(除了nodejs外，相信大部分也是在web端)
2. 逻辑复杂程度有多少？（是需要弱逻辑的引擎还是说需要在模板里做很多判断逻辑等，个人倾向弱逻辑的模板，业务逻辑还是在数据接口层做处理比较好）
3. 是不是有运行速度要求？（相信大部分都会选择是，也是一个考虑的重点）
4. 是不是需要预定义的模板？（是否需要预编译）
5. 需要Partials支持吗？(啥意思？不理解)
6. 需要DOM结构或者String字符串类型？
7. 除了模板标签，是不是在渲染前后开发语言一致？（就是前后台都用相同语法的引擎）