# iMkDocs

You can view on [doc site](https://vveicc.github.io/iMkDocs).

Just a template for doc site supported by [MkDocs](https://www.mkdocs.org).

To support LaTeX, I use [MathJax](https://www.mathjax.org) with the following code:

```javascript
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [['$','$'], ['\\(','\\)']],
      processEscapes: true
    }
  });
</script>

<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
```
