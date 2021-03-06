def prime?(number)
  if number < 2
     return false
  else 
    (2..number - 1).to_a.all? do |n|
      number % n != 0
    end
  end 
end

prime?(-1)
 end
 
 end
 


def Benchmark
benchmark=prime_integer
  puts [1,3,5]
  end
end


  def #prime?()
  puts 1,2,3,4,5
  returns prime integer
  end 
  
end

Benchmark.measure
end

# Implementing Prime

## Objectives

1. Practice iteration and looping.
2. Practice defining methods and controlling return values.

## Instructions 

Fork and clone this repository. Run the test suite to learn what is required of you. 

You'll be defining a method, `prime?()`, that takes in an integer argument and returns a boolean of whether or not that integer is a prime number.

A few things to think about:

* What defines an integer as a prime number? Research algorithms for how to determine if a number is prime.
* How do you create a range of numbers? How do you turn a range into an array so that it can be iterated over?

Requirements:

* Do not use any other Ruby library. You must build a method that can verify whether a number is prime. Don't `require 'math'` and just piggyback off their implementation of prime number.

## Advanced

Think about the efficiency of your algorithm. How many iterations does it do? Look into Benchmarking in Ruby and profile a few different approaches to implementing `prime?()`.

## Resources
* [Basic Benchmarking in Ruby](http://rubylearning.com/blog/2013/06/19/how-do-i-benchmark-ruby-code/)
* [Wikipedia](http://en.wikipedia.org/) - [Prime number](http://en.wikipedia.org/wiki/Prime_number)

<p class='util--hide'>View <a href='https://learn.co/lessons/prime-ruby'>Prime? Lab</a> on Learn.co and start learning to code for free.</p>
