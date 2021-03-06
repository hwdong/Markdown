# Markdown

[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

[Markdown入门](http://metman.info/blog/2013/02/27/markdownru-men/)


[MathJax with Jekyll](http://gastonsanchez.com/visually-enforced/opinion/2014/02/16/Mathjax-with-jekyll/): 只要修改_layouts文件夹中的page.html,插入如下代码就可以在githu pages中显示公式了。
```javascript
<script type="text/javascript"
    src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>
```
在_includes文件夹的 head.html中head加入([Mathjax inline mode not rendering](https://tex.stackexchange.com/questions/27633/mathjax-inline-mode-not-rendering))：
```javascript
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [ ['′,′'], ["\\(","\\)"] ],
      processEscapes: true
    }
  });
</script>
```

如何chrome浏览器中安装了mathjax插件，则可以直接如下输入公式([How to show math equations in general github's markdown(not github's blog)
](https://stackoverflow.com/questions/11256433/how-to-show-math-equations-in-general-githubs-markdownnot-githubs-blog),[Mathjax inline mode not rendering](https://tex.stackexchange.com/questions/27633/mathjax-inline-mode-not-rendering))：
```
$ \sum_{\forall i}{x_i^{2}} $
```
$ \sum_{\forall i}{x_i^{2}} $
```
$$a^2 + b^2 = c^2$$
```
$$a^2 + b^2 = c^2$$

[MathJax basic tutorial and quick reference](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)

[MathJax-在网页或MarkDown中插入数学公式](https://weilai5432.github.io/2017/01/11/MathJax-%E5%9C%A8MarkDown%E4%B8%AD%E6%8F%92%E5%85%A5%E6%95%B0%E5%AD%A6%E5%85%AC%E5%BC%8F/) 如: $x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$ 但需要你的chrome浏览器安装mathjax插件

[github的markdown文件中插入公式](http://www.wanguanglu.com/2016/07/18/github-markdown-equation/)，如：<img src="http://www.forkosh.com/mathtex.cgi?\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" style="border:none;">

[插入数学公式](http://www.jianshu.com/p/c169599726e1) 如：
<a href="https://www.codecogs.com/eqnedit.php?latex=ax^{2}&space;&plus;&space;by^{2}&space;&plus;&space;c&space;=&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?ax^{2}&space;&plus;&space;by^{2}&space;&plus;&space;c&space;=&space;0" title="ax^{2} + by^{2} + c = 0" /></a>

[norm](http://www.maths.tcd.ie/~dwilkins/LaTeXPrimer/BracketsNorms.html)

[LaTeX Math Symbols](http://web.ift.uib.no/Teori/KURS/WRK/TeX/symALL.html)

[argmin](http://tex.stackexchange.com/questions/5223/command-for-argmin-or-argmax)


