# Magic8Ball

This is a project I completed in the code academy course for python. The object is the create a program that can answer any “Yes” or “No” question with a different fortune each time.

* To start I created three variables: name, question and answer.
* Next I imported the random module so I could use the .randint() function which generates a random integer from a given range.
* After I imported the module, I created another variable random_number, that assigns the function call random.randint(1, 9) which generates a random number between 1 and 9.
* Next using control flow I used the if/elif/else statements to assign each number with an answer. To start I did an if statement so if the random_number is equal to 1 then the answer would be “Yes - definitely”
* From there I continued with elif statements through each number until 9 and assigned each a different answer.
* To end the if/elif/else statements I made an else statement that the answer was “Error”. This is so if a number was accidentally assigned to a number outside of the range of 1, 9 then Error would be printed.
* Next I started a new if statement so if the name is an empty string then it would print Question: then whatever answer. Else if name is provided is would print Name asks: answer.
* Then I created another new if statement in case the question is left empty it would print “The Magic 8-Ball cannot provide a fortune unless you ask it something”. Else it would print Name asks: question. Then it would print “Magic 8-Ball’s answer: answer.
      
