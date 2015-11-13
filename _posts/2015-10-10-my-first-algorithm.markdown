---
layout: post
title:  "My first Algorithm!"
date:   2015-10-10 14:48:07 +0000
categories: learning 
---
[Algorithms] are methods for solving problems that are suited for computer implementationa.

There are patterns in life, in nature, or simply just around us. A tree has a pattern, a flower has its pattern, even a life has a [pattern]. 
They are really well designed, by nature.

So what are we going to use patterns or algorithms to produce fruits, or the result?
Bubble sort, sometimes referred to as sinking sort, is a simple sorting algorithm that repeatedly steps through the list to be sorted, compares each pair of adjacent items and swaps them if they are in the wrong order. 
Here is my first [bubble sort][bubble-sort]
![IMAGE ALT TEXT](https://upload.wikimedia.org/wikipedia/commons/c/c8/Bubble-sort-example-300px.gif)
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
random_num = [1, 55, -1, 33, 77, -100, 2000, 85, 2,50, 1101]
  {% endhighlight %}

[bubble-sort]: //https://en.wikipedia.org/wiki/Bubble_sort
[Algorithms]: https://en.wikipedia.org/wiki/Algorithm
[pattern]: http://www.conwaylife.com/wiki/Conway's_Game_of_Life
