---
layout: post
title:  "My first Algorithm!"
date:   2015-10-10 14:48:07 +0000
categories: learning 
---
Algorithms are methods for solving problems that are suited for computer implementation.
There are patterns in life, in nature, or basically just around us. A blueberry tree has a pattern. Where is the root, how it is going to have a branch and when is it going to produce some fruits.
We saw small parts of the leaves, branches, the pockets: They kept repeating themselves.

So what are we going to use patterns or algorithms to produce....the result?

Here is my first [bubble sort].

{% highlight ruby %}
def bubble_sort(array)
   n = array.length
   (n-1).times do
     for j in 1..n-1 do
       if array[j-1] > array[j]
       array[j-1],array[j] = array[j],array[j-1]
       end
     end
   end
   array
end

def print_hi(name)
  puts "Hi, #{name}"
  end
  print_hi('Tom')
  #=> prints 'Hi, Tom' to STDOUT.
  {% endhighlight %}

[bubble sort] : //https://en.wikipedia.org/wiki/Bubble_sort


