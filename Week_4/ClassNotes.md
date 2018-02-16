### CLASS NOTES

## If:(algebraic logic)

```ruby

// if( some condition is true ){ do stuff in curly braces }
undefined
if (true){ console.log("the if statement is true")}
VM218:1 the if statement is true
undefined
if (false){ console.log("the if statement is true")}
undefined

# EXAMPLE

var hasFangs = false

if(hasFangs){
	console.log("That's a vampire")
} 
undefined
var hasFangs = true

if(hasFangs){
	console.log("That's a vampire")
} 
VM353:4 That's a vampire
undefined

# EXAMPLE

var hasFangs = false

if(hasFangs){
	console.log("That's a vampire")
} else {
	console.log ("That's a human")
}
VM427:6 That's a human

```

## If else if && console

```ruby

var hasFangs = true
var hasClaws = true

if(hasFangs){
	console.log("That's a vampire")
} else if(hasClaws){
	console.log("Werewolf")
} else if(hasFangs && hasClaws){
	console.log("That's a monster")
} else {
	console.log("That's a human")
}
VM969:5 That's a vampire

```

## If and ! means false 

```ruby

var hasFangs = true
var hasClaws = true

if(!hasFangs){
	console.log("That's a vampire")
} else if(!hasClaws){
	console.log("Werewolf")
} else if(hasFangs && hasClaws){
	console.log("That's a monster")
} else {
	console.log("That's a human")
}
VM971:9 That's a monster
undefined

```

## While

``` ruby

// while test condition is true, it do stuff in curly braces, if false, leaves the curly braces.

while(){ // test for a condition
// do something in here
      }

```

```ruby
sheepCounted ++ //shorthand for sheepCounted = sheepCounted + 1
```

```ruby
var sheepCounted = 0 

while( sheepCounted < 10 ){ 
      
console.log("I have counted " +
sheepCounted + " sheep!")

sheepCounted ++ 

}
VM1177:5 I have counted 0 sheep!
VM1177:5 I have counted 1 sheep!
VM1177:5 I have counted 2 sheep!
VM1177:5 I have counted 3 sheep!
VM1177:5 I have counted 4 sheep!
VM1177:5 I have counted 5 sheep!
VM1177:5 I have counted 6 sheep!
VM1177:5 I have counted 7 sheep!
VM1177:5 I have counted 8 sheep!
VM1177:5 I have counted 9 sheep!
9

```


## For

``` ruby

var timesToSayHello

// syntax: for(){...}

```

```ruby

var timesToSayHello

// do something FOR a count for "so many times"
for (var i = 0; i <timesToSayHello; i++){

}

```

```ruby
var timesToSayHello = 10

for (var i = 0; i < timesToSayHello; i++){
	console.log("Hello !")
} 
```


### Textwrangler stuff

## Prompt

```ruby

<!DOCTYPE html>
<html>
<head>
</head>
<body>

<p>This is before the script</p> 
<script> 

var myPhrase = "Hello Earthlings!"
console.log(myPhrase)

var name = prompt("What is your name?")
console.log("Hello " + name )

</script>
<p> This is after the script</p>

<body>
<html>

```

## Confirm

``` ruby

<!DOCTYPE html>
<html>
<head>
</head>
<body>

<p>This is before the script</p> 
<script> 

var likeComputers = confirm("Do You Like Computers?")

	if(likeComputers){
		console.log("Me Too Human")
	} else {
		console.log("I will destroy your data")
		
	}

</script>
<p> This is after the script</p>

<body>
<html>

```




