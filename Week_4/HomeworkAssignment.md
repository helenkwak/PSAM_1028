<!DOCTYPE html>
<html>
<head>
	<title> HangPrincess, The Guessing Disney Princess Version! </title>
</head>
<body> 
	<script type ="text/javascript">
	
var words = ["cinderella","snow white","ariel","belle","jasmine","rapunzel"]

var word = words[Math.floor(Math.random() * words.length)]

console.log("Random word is:" + word)

var answerArray = [] 

for (var i = 0; i <word.length; i++) 
	{ answerArray[i] = "_"
	}
	
var remainingLetters = word.length 

while (remainingLetters > 0 ){
	console.log("answerArray1 = " + answerArray)
	console.log("word.length = " + word.length)
	console.log("remainingLetters = " + remainingLetters) 
	
	alert(answerArray.join(" "))
	
	var guess = prompt("Guess a letter, or click the Cancel to stop playing")
	if (guess === null){ 
		break
		
	} else if (guess.length !==1 ){
		console.log("answerArray2 = " + answerArray)
		alert("Please enter a single letter.")
		
		} else { 
			for (var j = 0; j <word.length; j++) {
				if (word[j] === guess) {
					answerArray[j] = guess; 
					remainingLetters--;
					
					}
				}
			}
			
		}
		
alert(answerArray.join(" "))
alert("Good Job! You guessed: " + word )

</script> </body> </html>
		
	
