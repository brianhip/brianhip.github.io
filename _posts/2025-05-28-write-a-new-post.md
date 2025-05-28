---
title: Exploring Advanced MDX Features
date: 2025-05-27 10:00:00 -0600
categories: [Learning, Jekyll]
description: Short summary of the post.
tags: ["Advanced", "Diagrams", "Math", "Code"]
math: true
mermaid: true
---

## Exploring Advanced MDX Features

Let's demonstrate all the custom components we have available.

{% raw %}

```liquid
{% if product.title contains 'Pack' %}
  This product's title contains the word Pack.
{% endif %}
```

{% endraw %}

Next, a more complex mathematical expression:

<!-- Block math, keep all blank lines -->

$$
LaTeX_math_expression
$$

<!-- Equation numbering, keep all blank lines  -->

$$
\begin{equation}
  LaTeX_math_expression
  \label{eq:label_name}
\end{equation}
$$

Can be referenced as \eqref{eq:label_name}.

<!-- Inline math in lines, NO blank lines -->

"Lorem ipsum dolor sit amet, $$ LaTeX_math_expression $$ consectetur adipiscing elit."

<!-- Inline math in lists, escape the first `$` -->

1. \$$ LaTeX_math_expression $$
2. \$$ LaTeX_math_expression $$
3. \$$ LaTeX_math_expression $$

And another code example, this time in TypeScript:

```Javascript
const hello = "Hello World!\n";
console.log(hello);
```

```shell
echo 'No more line numbers!'
```

{: .nolineno }

## You can easily switch back to standard Markdown at any point.

- Diagrams help visualize processes.
- Math components make equations look professional.
- Code blocks are essential for tutorials.

Combining these elements makes your technical blog posts much more engaging!

---

This is the end of the post.
