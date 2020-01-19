## Welcome to my daily tech journal (written using less technical terms)

#### (14-01-2020): Differences between an Array and a LinkedList

- An array has an index but a linkedlist doesn't.
- Array's index makes getting a value of known index constant time. You must iterate through a linkedlist to get a value.
- You cannot run a binary search on a linkedlist because you neither know the size of the list nor its mid-position without transversing the list. You can run a binary/linear search on an array. You can only run a linear search on a linkedlist.
- Insertions or deletions from a linkedlist is faster because you just need to change the pointers, in an array, you must shift back the remaining part of the array.
- An array can be multidimensional. Linkedlist can be singly or doubly.

#### (15-01-2020): What does DOCTYPE mean in HTML?

Doctype is short for Document type. It is used to declare the version of HTML used by the document.

#### (16-01-2020): Blocks, Procs and Lambda in ruby, what's the deal?
##### Block

Blocks are quite polpular in ruby, if you are a ruby praogrammer, there is a chance that you used it already. A block is a code that is encapsulated between `do` and `end` or in between `{}`. If you have used `each` enumerable method, then you have used a block.

```ruby
array.each { |num| puts num }

array.each do |num|
  puts num
end
```
The code after the each between the `{}` or `do` and `end` -- `|num| puts num` is a block.

##### Lambda
