# Ruby Methods Code Challenge

## Objectives

1. Review `puts` method
2. Review explicit `return`

%%%

# Puts Method

Write a method that `puts` "ruby" 3 times.

~~~ruby

def puts_ruby_three_times
  # code your solution here
end

# do not remove the line below

puts_ruby_three_times

~~~solution

def puts_ruby_three_times
  3.times do
    puts "ruby"
  end
end

puts_ruby_three_times

~~~validation

assert_output(response, "ruby\nruby\nruby\n")

~~~

%%%

%%%

# Explicit Return

Write a method that returns 'ruby'

~~~ruby

def returns_ruby
  # code your solution here
end

# do not remove the line below

returns_ruby

~~~solution

def returns_ruby
  return "ruby"
end

returns_ruby

~~~validation

assert_output(response, "ruby")
assert_length(response, 4)

~~~

%%%

<a href='https://learn.co/lessons/demo-repl' data-visibility='hidden'>View this lesson on Learn.co</a>
