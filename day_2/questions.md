## Day 2 Questions

1. Create an array containing the following strings: `"zebra", "giraffe", "elephant"`.
```ruby
  ["zebra", "giraffe", "elephant"]
```
2. Save the array you created above to a variable `animals`.
```ruby
animals = ["zebra", "giraffe", "elephant"]
```
3. using the array `animals`, how would you access `"giraffe"`?
```ruby
animals[1]
```
4. How would you add `"lion"` to the `animals` array?
```ruby
animals.concat(["lion"])
```
5. Name and describe two additional array methods.

.map which is just like .each except it manipulates the array so it will iterate over the array for each item in the array and change it's value. .include? searches the array for any given argument and returns the appropriate boolean value.  

6. What are the boolean values in Ruby?

Boolean is either true or false and they each are their own data type.

7. In Ruby, how would you evaluate if `2` is equal to `25`? What is the result of this evaluation?

```ruby
2 == 25
false
```

8. In Ruby, how would you evaluate if `25` is greater than `2`? What is the result of this evaluation?

```ruby
25 > 2
true
```
