---
layout: post
date: 2015-12-4 12:00:00 +0000
title: "Oh, it is December already!"
---

Hold on, you need to wake me up when September ends! It is December already!

Anyway, keep learning!!

#What is an operator?

Programming languages typically support a set of operators: constructs which behave generally like functions, but which differ syntactically or semantically from usual functions. Common simple examples include arithmetic (addition with +, comparison with >) and logical operations (such as AND or &&). More involved examples include assignment (usually = or :=), field access in a record or object (usually .), and the scope resolution operator (often ::). Languages usually define a set of built-in operators, and in some cases allow user-defined operators.

Ruby supports a rich set of operators, as you'd expect from a modern language. Most operators are actually method calls. For example, a + b is interpreted as a.+(b), where the + method in the object referred to by variable a is called with b as its argument.

#Something interesting learnt today:
Ruby's bitwise operators
{% highlight ruby %}
13.to_s(2)  #=> "1101"
{% endhighlight %}
 & The **AND** operator <br>
 | The **OR** operator <br>
 ^ The **XOR** operator <br>
 ~ The **NOT**(complement operator) <br>

An example:
{% highlight ruby%}
(a = 18).to_s(2)  # => "10010"
(b = 20).to_s(2)  # => "10100"
(a & b).to_s(2)   # => "10000"
(a | b).to_s(2)   # => "10110"
{% endhighlight %}
# Vim learning today

Display line numbers and disabling

- :set number or :set nu
- :set nonumber or :set nonu

