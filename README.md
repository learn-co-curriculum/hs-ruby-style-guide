---
  tags: style, kids
  languages: ruby
---

##Ruby Style Guide

I'm going to go through a few basic best practices that you should use when writing Ruby code.

Let's start with defining methods. When you define a method, you use the def keyword, and follow it with the name of the method, right? Well, if your method takes an argument, please put your parentheses exactly after the method name. Don't put a space in between, directly plug in the parentheses.

Something like this should do: 

```ruby
def my_method(argument1)
end
```

Don't make the first letter of your method name capital, leave it lower case, unless it's a class because classes are cooler than methods. Using camelCase is good practice in the programming community. If your method name needs to be more than one word, do something like this:

```ruby
def more_than_one_word
end
```

Instead of something like this:

```ruby
def morethanoneword
end
```

or even worse:

```ruby
def MORETHANONEWORD
end
```

Please indent with two spaces inside of a method, an if statement, a for loop, or anything else that transcends one line.

```ruby
if "flat" + "iron" == "flatiron"
  puts "yay!"
end
```

Why do we need to follow these simple style rules when writing your Ruby code? You need to be mindful of other programmers. If you ever ask for help and your code is just completely ugly, you'll be making it much harder for the person helping you. Or when you're working at a tech place, where you somehow managed to land a job, and you're assigned a partner to build a program with... if your part of the code is completely ugly, it'll be much harder to maintain consistency.

So don't be selfish, follow these simple rules and thank me later. If you ever need a reference, come back to this page. 


