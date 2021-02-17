This is an example github pages + mathjax file. The $ $ inline and the $$ $$ display equations work fine. 

When $a \ne 0$, there are two solutions to $ax^2 + bx + c = 0$ and they are
$$x_{1,2} = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

When $a \ne 0$, there are two solutions to $ax^2 + bx + c = 0$ and they are
$$x_{1,2} = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

Althought it requires to place the following code at the and of every .md file, really ugly and not practical

```
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
      tex2jax: {
        inlineMath: [ ['$', '$'] ],
        displayMath: [ ['$$', '$$'], ["\\(","\\)"] ],
        processEscapes: true,
    }
  });
</script>

<script type="text/javascript" async
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=default">
</script>
```
You can see that this exact file gets really ugly on [github's default interface](https://github.com/bmacho/github-pages-test/blob/main/README.md)

<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
      tex2jax: {
        inlineMath: [ ['$', '$'] ],
        displayMath: [ ['$$', '$$'], ["\\(","\\)"] ],
        processEscapes: true,
    }
  });
</script>

<script type="text/javascript" async
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=default">
</script>
