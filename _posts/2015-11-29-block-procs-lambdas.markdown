---
layout: post
title: "Blocks Procs ^Lambdas"
date: 2015-11-30 9:00:00 +0000
---
#Lambda

Lambda is also a type of "closure". A closure is basicall a formal, computer-science way of saying " a chunk of code that you can pass around but which hangs onto the bariables that you giave it when you first called it."

If Procs are sort of a more-fleshed-out version of blocks, then lambdas are sort of a more-fleshed-out version of Procs. They are one step closer to being actual methods themselves, but still technically count as anynymous functions.

- A lambda gives you more flexibility with what it returns(like if you want to return multiple
values at once) because you can safely use the explicit *return* statement inside of one.
With lambas, *return* will only return from the lambda itself and not the enclosing method, which is what happens if you use *return* inside a block or Proc.
{% highlight ruby%}
lambda do |word|
  puts word
  return word    #you can do this in lambda
  end.call("Emily is learning lambda")  
Emily is learning lambda => "Emily is learning lambda"  #not nil
{% endhighlight %}

#Vim learning today
How to insert '#' or anything in front of multi-lines

- On a character in the first line, press Ctrl-V 
- Move with *h,j,k,l* to select a few empty lines
- You can also press *$* to extend the visual block to the end of each line
- Press **A** then space then Ctrl-R **#** then Esc
