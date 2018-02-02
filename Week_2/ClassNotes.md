This is my code snippet:

```ruby

var firstName = "Helen"
undefined

var lastName = "Kwak"
undefined

var fullName = firstName + lastName
undefined

fullName
"HelenKwak"

var firstLetter = firstName.slice(0,1)
undefined

var lastLetter = lastName.slice(0,1)
undefined

var monogram = firstLetter + lastLetter
undefined

var monogram = firstLetter + lastLetter
undefined

monogram
"HK"

```

## And then we did this:
```ruby

var secondsInAMinute = 60
undefined
var minutesInAnHour = 60
undefined
secondsInAnHour = secondsInAMinute + minutesInAnHour
120
secondsInAnHour = secondsInAMinute * minutesInAnHour
3600
var hoursInADay = 24
undefined
var secondsInADay = secondsInAHour * hoursInADay
VM1101:1 Uncaught ReferenceError: secondsInAHour is not defined
    at <anonymous>:1:21
(anonymous) @ VM1101:1
var secondsInADay = secondsInAnHour * hoursInADay
undefined
secondsInADay
86400
minutesInAnHour
60
var daysInAYear
undefined
var daysInAYear = 365
undefined
var secondsInAYear = secondsInADay * daysInAYear
undefined
secondsInAYear
31536000
var theirAge = 77
undefined
their
VM1319:1 Uncaught ReferenceError: their is not defined
    at <anonymous>:1:1
(anonymous) @ VM1319:1
theirAge * secondsInAYear
2428272000
var myAge = 20
undefined
myAge * secondsInAYear
630720000

```
