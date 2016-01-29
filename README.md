

### Ruby Style Guide
<img src="https://after-school-assets.s3.amazonaws.com/style.png" width="200px" align="right" hspace="10">When you're coding, it's easy to write your methods and classes without giving much thought to how the code actually *looks* in the file. But, being mindful of how you lay out the code - where you put your indentations, parentheses, hard returns, etc. - makes your code much more readable. That'll make you and the coders you work with much happier down the road because it'll be much easier to understand what is happening in your code. Here are a few style pointers...

### Defining Methods
Let's start with defining methods. When you define a method, you use the `def` keyword, and follow it with the name of the method, right? Well, if your method takes an argument, please put your parentheses *exactly after the method name*. Don't put a space in between; directly plug in the parentheses.

Something like this should do: 

```ruby
def my_method(argument1)
end
```

The first letter of a method is always lowercased, unless you're writing a class because classes are cooler than methods. Class names are always capitalized. In method names, `snake_case_is_best_practice`. If your method name needs to be more than one word, do something like this:

```ruby
def more_than_one_word
end
```

Instead of something like this, which is _not_ snake cased:

```ruby
def morethanoneword
end
```

or even worse:

```ruby
def MORETHANONEWORD
end
```
###Defining Classes
On the other hand, class names are **Capitalized and CamelCased**. That means that if you're using multiple words to name your class, push them right up against eachother and capitalize each new word. Your class would look like this:
```ruby
class MyAwesomeClass
end
```
### Two Space Indentations
Lastly, please indent with **two spaces** inside of a class, amethod, an if statement, a for loop, or anything else that transcends one line.

```ruby
if "flat" + "iron" == "flatiron"
  puts "yay!"
end
```
### Wrap Up
Why do you need to follow these simple style rules when writing your Ruby code? You need to be mindful of other programmers. If you ever ask for help and your code is just completely ugly, you'll be making it much harder for the person helping you. Or when you're working at a tech company and you're assigned a partner to build a program with... if your part of the code is completely ugly, it'll be much harder to maintain consistency and clarity.

So don't be selfish, follow these simple rules and thank me later. 



<p data-visibility='hidden'>View <a href='https://learn.co/lessons/hs-ruby-style-guide' title='Ruby Style Guide'>Ruby Style Guide</a> on Learn.co and start learning to code for free.</p>
