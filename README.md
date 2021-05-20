# My 4 Favorite Ruby Methods
### `zero?`
Returns a `true` boolean if the `Float` returns 0. Otherwise, it returns `false`.
```ruby
0.0.zero? #=> true
3.829.zero? #=> false
```

### `next_year`
This method is called on a Ruby `date` object and it returns that date one year in the future.
```ruby
Date.new(2014, 8, 9).next_year #=> #<Date: 2015-08-09 ...>
```

### `.nil?`
This method can be caleed on any Ruby `Object` and return a boolean if that object is `nil` or not.
```ruby
"string".nil? #=> false
0.nil? #=> false
Object.new.nil? #=> false
nil.nil? #=> true
```

### `puts`
This method prints out whatever you write after it.
```ruby
puts "Hello, World!" #=> Hello, World!
puts "Gordon is a genious" #=> Gordon is a genious
```