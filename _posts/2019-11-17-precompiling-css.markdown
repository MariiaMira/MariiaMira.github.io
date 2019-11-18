---
layout: post
title: Precompiling CSS
date: 2019-11-17
---

What do you think of pre-compiling your CSS?

* Compare to regular CSS
* Which techniques did you use?
* Pros and cons?

So far CSS preprocessing is more complicated for me in comparison with using simple CSS but it is mostly because I am not used to this way of setting styles.
One of the biggest diadvantages for me is a big amount of files, difficult to find what exactly I want to change and to understand what exactly works wrong.
On one hand variables are very convenient and save the time on looking for the right parameter, but on the other hand it is still quite complicated,
therefore I haven't used any variables of my own yet, but of course I will apply them later.

The thing I find very convenient is nestig, so I can avoid complicated synntax and use

~~~~
body {
  header {
    some styles...
  }
  div {
    more styles for div element
  }
}
~~~~

Having several files is also an advantage if one gets used to it becase then one can devide the code into some logical parts. For example common styles for all the pages,
styles for posts, styles for footer, etc.
There is also a nice property of using operators, that allows to make pictures for example twice as big as the header, etc.

So I would say that so far the biggest difficulty with SCSS for me is the lack of understanding and experience.