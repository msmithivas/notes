# Ruby Notes

## Data Types

### Hashes
A hash is a collection of key-value pairs.
Keys and values can be of any data type.
Hashes can be created using the {} or Hash.new syntax.
Elements of a hash can be accessed using the [] syntax.

```ruby
# Creating a hash
person = { name: "John", age: 30, city: "New York" }

# Accessing elements of a hash
puts person[:name]  # "John"
```

### Sets

A set is a collection of unique elements.
Sets can be created using the Set.new syntax.
Elements can be added to a set using the .add method.

```ruby
# Creating a set
fruits = Set.new(["apple", "banana", "orange"])

# Adding an element to a set
fruits.add("pear")
```

## Syntax

### Conditionals
The if statement is used for conditional execution of code.
The if statement can be followed by an optional else clause.
The elsif clause can be used for multiple conditions.
The ternary operator (?:) can be used as a shorthand for simple if/else statements.

```ruby
# Using if/else statements
if grade >= 90
  puts "A"
elsif grade >= 80
  puts "B"
else
  puts "C"
end

# Using the ternary operator
result = (score >= 60) ? "pass" : "fail"
```

### Loops
The while loop is used to execute a block of code while a condition is true.
```ruby
# Using a while loop
i = 0
while i < 10
  puts i
  i += 1
end

# Using a for loop
for i in 1..5
  puts i
end

# Using the each method
fruits = ["apple", "banana", "orange"]
fruits.each do |fruit|
  puts "I like #{fruit}s!"
end
```

### Methods

A method is a reusable block of code.
Methods are defined using the def keyword.
Methods can have parameters.
Methods can return values using the return keyword.

```ruby
# Defining a method
def square(number)
  return number ** 2
end

# Using a method
result = square(5)
puts result  # 25
```
