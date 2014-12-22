EasyCast
========

Makes math operations in Swift easier by adding automatic casting between Int, Float, CGFloat, and Double


### Usage

Instead of:

```
var sum = CGFloat(myInt) + CGFloat(myFloat)
```

Just do:

```
var sum = myInt + myFloat
```


That's pretty much it



### When to use this
* Swift's type-safety is littering your code base with obvious casts.
* You are working on something where making some type assumption isn't a problem.
* You know how it works.

### When not to use this
* You want type-safety above all else.
* You are working on scientific or academic software.
* You don't know how it works,