## Arrays:

```ruby

var myFruitArray = ["Apple","Banana","Coconut","Divine Fruit","Earlobe Grapes","Figs"]
undefined
myFruitArray
(6) ["Apple", "Banana", "Coconut", "Divine Fruit", "Earlobe Grapes", "Figs"]
myFruitArray[2]
"Coconut"
myFruitArray[2] = "My Change"
"My Change"
myFruitArray[5] = "Last Fruit"
"Last Fruit"
myFruitArray
(6) ["Apple", "Banana", "My Change", "Divine Fruit", "Earlobe Grapes", "Last Fruit"]

```

## Length:

```ruby

var myFruitArray = ["Apple","Banana","Coconut","Divine Fruit","Earlobe Grapes","Figs"]
undefined
myFruitArray.length
6

```

## Nesting:

```ruby

var myNestedArrayofFruit = []
undefined
var myNestedArrayofFruit = ["","",""]
undefined
var myNestedArrayofFruit = [["","",""],["","",""],["","",""]]
undefined

```

## .push - adding to END of Array

```ruby

// .push adds Elements to END of Array
var mySimpleFruitArray = []
undefined
mySimpleFruitArray.push()
0
mySimpleFruitArray.push("Apple")
1
mySimpleFruitArray
["Apple"]
mySimpleFruitArray.push("Apple")
mySimpleFruitArray.push("Carrot")
mySimpleFruitArray.push("Kiwi")
mySimpleFruitArray.push("Orange")
5
mySimpleFruitArray
(5) ["Apple", "Apple", "Carrot", "Kiwi", "Orange"]
0
:
"Apple"
1
:
"Apple"
2
:
"Carrot"
3
:
"Kiwi"
4
:
"Orange"
length
:
5
__proto__
:
Array(0)

```

## .unshift - adding to FRONT of array

```ruby

// ADD ELEMENT TO Front, Shift it All Down
undefined
var colorArray = ["Red","Green","Blue"]
colorArray.unshift("Yellow")
4
colorArray
(4) ["Yellow", "Red", "Green", "Blue"]
colorArray.unshift("Purple")
5
colorArray
(5) ["Purple", "Yellow", "Red", "Green", "Blue"]

```

## .pop - removing from the END of array

```ruby

// .pop REMOVING Elements from END of An Array
var colorArray = ["Red","Green","Blue"]
undefined
colorArray.pop
ƒ pop() { [native code] }
colorArray.pop()
"Blue"
colorArray
(2) ["Red", "Green"]
colorArray.pop()
"Green"
colorArray
["Red"]
colorArray.pop()
"Red"
colorArray
[]
colorArray.push("Grey")
1
colorArray.push("Yellow")
2
colorArray
(2) ["Grey", "Yellow"]

```

## .concat 

```ruby

// Concatenate, or Attached, 2 Arrays
var ledColorArray = ["Red","Green","Blue"]
var grayscaleArray = ["White","Gray","Black"]
var myLargeColorArray = ledColorArray.concat(grayscaleArray)
undefined
myLargeColorArray
(6) ["Red", "Green", "Blue", "White", "Gray", "Black"]

```

## .indexOf - searching arrays with strings

``` ruby

var ledColorArray = ["Red","Green","Blue"]
undefined
ledColorArray.indexOf("Red")
0
ledColorArray.indexOf("red")
-1
ledColorArray.indexOf("Blue")
2

```

## .join - combining sentences

```ruby

var ledColorArray = ["Red","Green","Blue"]
undefined
ledColorArray.join(" Is Nicer Than ")
"Red Is Nicer Than Green Is Nicer Than Blue"
ledColorArray.join(" ? ")
"Red ? Green ? Blue"

```

## Math.random() - random numbers 

```ruby

Math.random() * 10
(random number between 1 and 10)

```

## Math.floor(9.99999) - rounds numbers

```ruby

Math.floor(9.99999)
9

```

## combining Math.floor and Math.random()

```ruby

Math.floor(Math.random()*10)
3
Math.floor(Math.random()*10)
8
Math.floor(Math.random()*10)
4
Math.floor(Math.random()*10)
9
Math.floor(Math.random()*10)
9

```

