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

## adding to END of Array

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

## adding to FRONT of array

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

## removing from the END of array

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
