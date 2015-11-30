---
layout: post
title: "Blocks ^Procs Lambdas"
date: 2015-11-26 12:00:00 +0000
---
# 2 PROC
In short, Procs are reusable code. The only difference between blocks and Procs is that block is a Proc that cannot be saved.
**Proc** is written as uppercase because it is a proper class within Ruby. However, blocks do not have a class of their own.
{% highlight ruby %}
def what_am_i(&block)
block.class
end
puts what_am_i {}
# => Proc
{% endhighlight %}
When should we use blocks over Procs <br>
1. Block: Your method is breaking and object into smaller pieces, and you want to let your users interact with these pieces <br>
2. Proc: You want to reuse a block of code multiple times.

#Vim learning today

1 Save file under different location

- :pwd to display the current working directory
- change working direcotry with :cd path/to/new/directory
- Or enter the full path :w /var/www/filename

2 In certain line use **f** then the letter we want, this will only search the letter after the cursor.

