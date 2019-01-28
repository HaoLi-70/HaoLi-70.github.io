---
layout: post
title:  "The Zeeman and Paschen-Back Effects"
date:   2019-01-28
excerpt: "Just about everything you'll need to style in the theme: headings, paragraphs, blockquotes, tables, code blocks, and more."
tag:
- polarization 
- magnetic field
comments: true
---

# Hamiltonian
The total Hamiltonian $$ H $$ of an atomic system in a magnetic field is given by

$$ H=H_0+H_B, $$

where $$ H_0 $$ and $$ H_B $$ are the unperturbed and magnetic Hamiltonians, respectively. The magnetic Hamiltonian $$ H_B $$ is given by 

$$ H_B=\frac{e_0h}{4\pi mc}(\vec{L}+2\vec{S})\cdot\vec{B}+\frac{e_0^2}{8mc^2}(\vec{B}\times\vec{r})^2.$$

The second term is the so called diamagnetic term, and not important except for extremely large fields. If the diamagnetic term is neglected, the magnetic Hailtonian can be written as

$$ H_B=\frac{e_0h}{4\pi mc}(\vec{L}+2\vec{S})\cdot\vec{B}=\nu_0(\vec{L}+2\vec{S})\cdot\vec{B}. $$

The matrix element is given by

\\[ <\alpha JM|H_B|\alpha JM'>=\nu_0B<\alpha JM|(\vec{J}+\vec{B})\cdot \vec{b}|\alpha JM'> \\]

where $$ \vec{b} $$ is a unit vector in the magnetic field direction.

# Zeeman Effect

# Paschen-Back Effect



### Body text

Lorem ipsum dolor sit amet, test link adipiscing elit. **This is strong**. Nullam dignissim convallis est. Quisque aliquam.

![Smithsonian Image](https://mmistakes.github.io/minimal-mistakes/images/3953273590_704e3899d5_m.jpg)
{: .image-right}

*This is emphasized*. Donec faucibus. Nunc iaculis suscipit dui. 53 = 125. Water is H2O. Nam sit amet sem. Aliquam libero nisi, imperdiet at, tincidunt nec, gravida vehicula, nisl. The New York Times (That’s a citation). Underline.Maecenas ornare tortor. Donec sed tellus eget sapien fringilla nonummy. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus.

HTML and CSS are our tools. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus. Praesent mattis, massa quis luctus fermentum, turpis mi volutpat justo, eu volutpat enim diam eget metus.

### Blockquotes

> Lorem ipsum dolor sit amet, test link adipiscing elit. Nullam dignissim convallis est. Quisque aliquam.

## List Types

### Ordered Lists

1. Item one
   1. sub item one
   2. sub item two
   3. sub item three
2. Item two

### Unordered Lists

* Item one
* Item two
* Item three

## Tables

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|----
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=====
| Foot1   | Foot2   | Foot3
{: rules="groups"}

## Code Snippets

{% highlight css %}
#container {
  float: left;
  margin: 0 -240px 0 0;
  width: 100%;
}
{% endhighlight %}

## Buttons

Make any link standout more when applying the `.btn` class.

{% highlight html %}
<a href="#" class="btn btn-success">Success Button</a>
{% endhighlight %}

<div markdown="0"><a href="#" class="btn">Primary Button</a></div>
<div markdown="0"><a href="#" class="btn btn-success">Success Button</a></div>
<div markdown="0"><a href="#" class="btn btn-warning">Warning Button</a></div>
<div markdown="0"><a href="#" class="btn btn-danger">Danger Button</a></div>
<div markdown="0"><a href="#" class="btn btn-info">Info Button</a></div>

## KBD

You can also use `<kbd>` tag for keyboard buttons.

{% highlight html %}
<kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd>
{% endhighlight %}

Press <kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd> to move your car. **Midtown Maddness!!**


