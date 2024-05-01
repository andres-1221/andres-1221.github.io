---
layout: post
title: What is Serpiente?
#subtitle: There's lots to learn!
#gh-repo: daattali/beautiful-jekyll
#gh-badge: [star, fork, follow]
#tags: [test]
comments: false
mathjax: true
#author: 
---

{: .box-success}
Serpiente is a programming language inspired by Python, designed with the goal of making coding more accessible to Spanish-speaking programmers and beginners. The name "Serpiente," which means "snake" in Spanish, is similar to Python's language design and syntax. Serpiente aims to lower the barrier to entry for Spanish speakers entering the world of programming. With its easy-to-read code structure, Serpiente provides a welcoming environment for newcomers to learn and explore the fundamentals of coding while empowering Spanish-speaking developers to express their ideas and solutions effectively.

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
