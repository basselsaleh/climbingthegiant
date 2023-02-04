---
aliases:
- /markdown/2021/05/03/first-post
categories:
- markdown
date: '2021-05-03'
description: My first post, just a test
layout: post
title: Hello World!
toc: true

---

# Hello World!

So here it is, my first blog post. More likely than not this particular post will have a short life, and I'll delete it once I create my first **hIgH quAliTy** blog post. I have used markdown a little bit before, mostly for making hastily thrown together `README` files for repos that I never made public anyway. It seems pretty intuitive to use so far. Let's test some features.

## Lists

Big fan of itemization. Thankfully with markdown this is easy to do and make pretty:

- For example, this is the first item of a list.
- This is the second.

## Code

I don't imagine I'll be integrating code *too* often, but perhaps I'll make some simple tutorials in the future for libraries I like/workflows I find useful.

Here's some `Python` code:

```python
def funky(x):
	return str(x) + 'is a funky monkey'

# will a comment show up?
print(funky(6))
```

Does `Julia` syntax work?

```julia
function julia_funk(x)
	x = "funkalicious"
end

# julia comment
x = julia_funk(6)
```

## Math

So Jekyll uses a markdown parser called `kramdown`, which supports MathJax. In theory I can render \\(\LaTeX\\) stuff like so:

$$
-\frac{\hbar^2}{2m}\nabla^2\Psi = i\hbar\frac{\partial}{\partial t}\Psi \\
$$

## Pictures

Okay final test for now. Let's insert a big picture of my face. And then figure out how to make it less big later.

![](giantshoulders.jpeg "my face")

Turns out it made the picture the perfect size. This is all working so well so far!

I'm currently building the site locally and viewing it in the browser using a Jekyll server inside a docker thing... I just followed some tutorials and set it up. Once I push the changes this should be reflected on the live site.