---
layout: post
title: "^Block Proc and Lambda"
date: 2015-11-25 8:00:00 +0000
---

# 1 BLOCK 

Blocks, Procs and Lambdas in Ruby can be confusing, but as many things in life, the best way to conquer them is to understand them first.

Ruby code blocks are chunks of code between<br>
- **{ }**  for single line blocks or <br> 
- between **do - end**  for multi-line blocks <br>
that you can associate with *method invocations*, almost like a method call.

A block is written starting on the same line as the method call's las parameter.
{% highlight ruby %}
x = 100
5.times do |x|
  puts "x inside the block: #{x}"
end

puts "x outside the block: #{x}"
{% endhighlight %}

What do you expect the outcome to be? Here is the result:

x inside the block : 0 <br>
x inside the block : 1 <br>
x inside the block : 2 <br>
x inside the block : 3 <br>
x inside the block : 4 <br>
x outside the block : 100

A block is just part of the *syntax* of a method call. It doesn't mean anything on a standalone basis and can only appear in argument lists.

{% highlight ruby %}
array = [1,2,3,4]
array.collect! do |n|
n**2
end
puts array.inspect
# -> [1,4,9.16]
{% endhighlight %}

#Vim learning today
- edit a file until you like it
- *:w another-file* to use it as a starting point for *another-file*
- if the file exits already, you need to add ! to overwrite it if you want
- *:e another-file* to polish up *another-file*
