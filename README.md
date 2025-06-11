
# doodles

This is a doodles file.

:)

This sentence uses `$` delimiters to show math inline: $\sqrt{3x-1}+(1+x)^2$

This sentence uses $\` and \`$ delimiters to show math inline: $`\sqrt{3x-1}+(1+x)^2`$

The following entry uses two dollar symbols $$ to delimit a math expression and render it as a block.

$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$

The following entry uses the ```math code block syntax to display a math expression as a block.
With this syntax, you don't need to use $$ delimiters.

```math
\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
```

This expression uses `\$` to display a dollar sign: $`\sqrt{\$4}`$

To split <span>$</span>100 in half, we calculate $100/2$

This is a piece of Liquid code: [{{ "hello, world !" | capitalize }}].

This is some embedded HTML:
<h1>Hello</h1>
<ul>
  <li><b>Item 1 is bold</b></li>
  <li class="done">Item 2 is styled</li>
  <li><a href="#">Item 3 is a link</a></li>
  <li id="_id-foobar">Item 4 has javascript interactivity</li>
</ul>
<style>
  .done {
  color: darkseagreen;
  text-decoration: line-through solid black 2px;
}
</style>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
<script>
  $(function() {
    $("#_id-foobar").on("click", doSomething);
    function doSomething() {
      console.log("Doing something here.");
    }
  });
</script>
