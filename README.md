# Ruby Cheatsheet

Topics:

## Data types
### Strings
[Ruby docs Strings] (https://ruby-doc.org/core-2.4.1/String.html)


Double quote *strings*

```ruby
"Hello World"
```

Single quote strings **string**
```ruby
'Hello World' 
```

puts creates a new line e.g.

print does not  e.g

Concatating **strings**

"String" + "String"
```ruby
"Hello" + "World"
= "HelloWorld"
```
**Interpolation** is used to incoporate a variable into a string using #{Variable} 
```ruby
food = Burger
Puts "I would love to eat a #{food} right now!"
=> I would love to eat a Burger right now!
```
**NOTE** Interpolation does not work in strings that have single qoutes eg.

Tips: 
- Use  \ character to show ignore characters e.g.
```\t t' \\```


- List of string methods
    - .reverse
    - .upcase
    - .downcase
    - .capitalize
    - .to_i

    

### Integers
[Ruby Docs Integers] (http://ruby-doc.org/core-2.4.1/Integer.html)

- Variable
```ruby
result = 5 + 5
```

```+=```  Adds "" increments to a variable e.g.


```ruby

```

```*=```  Multiplies "" increments to a variable e.g.

Tips: 

- When ``` puts ``` is used to show a integer or float, the ```puts``` method will show it as a string and needs to be converted to an integer to use operators on e.g.
``` x = 2 
puts x
=> "2"

x = 2 
puts x.to_i
=> 2
```

-```puts``` coerces everything into strings

- List of String methods:
    - .to_s (To string)
    - .to_f (To float)
    - .to_i (To Integer)


### Floats
[Ruby Docs Floats] 
(https://ruby-doc.org/core-2.4.1/Float.html)

Tips: 

- When a ```float``` is used in an equation the result


- List of Floats methods:
    -

### Booleans

Tips: 

- All values default to ```true```. e.g.
```
hello = true
=> true
```

- The values of ```nil``` and ```false``` default to ```false```.

```
hello = false
=> false

hello = false
=> false
!hello
=> true

!!hello
=>false

hello = !hello
=> true
```



### If/ Else
[Ruby Docs Integers] (https://ruby-doc.org/core-2.4.1/doc/syntax/control_expressions_rdoc.html)

If statements take booleans

```ruby
steve = "paid"
if steve == "paid"
    puts "drinks for everyone"
    else
    puts "ha" 
    elsif steve == "paid more money today".
    puts "cry with joy"
end
```
### Loops

while continues until

until continues until there is a false result

```ruby
running = true
car_choices = []
while doing_its_thing

puts """ Enter in your choice (pick a number)

    1. Ford Falcon
    2. Holden Commodore
    3. Skyline
    4. Telsa Model S


    response = gets.chomp.to_i
    puts "your response was #{response}"
if car_choices.includes? responce
case response
    when 1
        car_choices.push "Ford Falcon"
    when 2
        car_choices.push "Ford Falcon"
    when 3
        car_choices.push "Skyline"
    when 4
        car_choices.push "Tesla Model S"
    end
    
    car_choices.each do|car_choice|
        puts car_choices
    end
    if car_choices.length == 3
    break
end

    car_choices.push response
    doing_its_thing = false
end
```

### Operators ( >= or &&)

== does it equal (is it the same)
!= does not equal

- greater than or equal to
```ruby
10 >= 10 
=> true
```
&&
```ruby
10 >= 10 && 9 < 10
=> true
```

### arrays

Variables are better to use for multiple responces.

array = []

or array %w{}   best to use the other and is hard to distinguish what it is

 - methods


### Maths stuff

#### And things


                                |  &&  | True  | False |
                                |------|-------|-------|
                                | True | True  | False |
                                | False| False | False |

#### Or things

                                |  Or  | True  | False |
                                |------|:-----:|-------|
                                | True | True  | True  |
                                | False| True  | False |
                                

## Glossary
|   Term    |          Definition               |
|-----------|:----------------------------------|
| Constant  | A variable that doesn't change.    |
| Ternery Operator  | expects a true or false, question mark followed by a true statement - colon - and a flase statement.|| Recursion| It's calling a function within a function |  