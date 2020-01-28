
# E02a-Control-Structures

This is an assignment for my Game Technology class. I was to fork this repository to my own Github account and answer questions requarding the all the different files along with it. I have done so down below by changing this README file. 

- Open main01.py. Before running it, what do you expect this program to do?
      It will display the message "Greetings!" and ask me to input my favorite color, it doesn't look like it will do anything with my input. 
  - Now right click on the main1.py window and select “Run Python File in Terminal”. Click in the bottom panel, and answer the question. Describe what happened.
      Nothing happened after I answer the question.  
  - What do you think the program did with what you typed in answer to the question?
      It didn't do anything with it. 
- Open main02.py. Before running it, describe how this is different than main01.py.
      It stores the input in a vairable called "color" and it has a line to print said vairable. 
  - What do you think the color = input() will do?
      It will store what I input behind the varaible "color" and the next line will display it.
  - Run the program in the terminal and answer the question. Did the program do what you expected?
      Yes.
- Open main03.py. Before running it, describe how this is different than main02.py.
      Instead of of have code to print what you type it has a statement to check and see if you entered "Red" and spits out a different response based on if you did or not.
  - What is happening on lines 9–12?
      It code to see if the user inputed "Red" and gives a different response based on what was entered
  - Why are lines 10 and 12 indented?
      So python nows it's part of the statement 
  - Run the program and answer the question. What happens if you don’t capitalize Red?
      It says "Sorry, try again." 
  - What does this tell you about "color"?
      It wants you to enter red
- Open main04.py. Before running it, describe how this is different than main03.py.
      It accepts both "Red" and "red" as correct answers now 
  - What problem is this trying to solve?
      That python is case senstive and sees Red and red as two different things 
  - Run the program and answer the question. What happens if you use some other capitalization scheme (i.e., “RED” or “reD“)?
      It says "Sorry, try again."
- Open main05.py. What do you expect line 9 to do?
      It sets what you type to lowercase to get around the case sensitivity 
  - What problem is it trying to solve?
      It's trying to get around python's problem with how it see cases differently
  - Run the program and answer the question. What happens if you add spaces before or after the word (i.e., “ RED “ or “ red”)?
      It says "Sorry, try again."
 - Open main06.py. How is line 9 different than in main05.py?
      Instead of color.lower(), it's color.lower().strip()
   - What would you guess .strip() is doing?
      It takes away any extra spacing around the user's input
   - Run the program and answer the question. Is there another way of writing “red” that will break this logic?
      Entering it as "R E D" breaks it
 - Open main07.py. Before running this program, how do you expect this to be different than main06.py?
      It has an added text option if you enter "pink"
   - What is happening on line 12?
      There is a secoundary if statment to see if it's "pink"
   - Run the program and answer the question.
      I did and entering pink did bring the new result of "Close!"
 - Open main08.py. What is the purpose of line 9?
      Instead of it being "if" it is "while" so the user will keep guessing until it they guess red
   - Why are lines 10–17 indented?
      So python knows those lines of coode only are in effect if the while statment is true
   - Run the program. What would happen if line 10 were moved before line 9 (and no longer indented)?
      If they guessed wrong they would be trapped in the loop and unable to change there answer 
   - Make that change and run the program again. (To end any Python program, you can type ctrl-c)
      If you guess wrong it will say "Sorry, try again." over and over and never stop. 
 - Open main09.py. What is happening on line 13?
      There is a new vairable, "count", that is increased by one each time it goes through the loop.
   - What is the purpose of “count”?
      It serves to count the number of attempts it take for the user to guess correctly.
   - What is happening on line 22?
      There is nothing on line 22 but line 21 will display how many attempts it took along with a short message along with it.
   - Run the program.
      After I guess it correctly it told me how many attempt is took, I messed up on purpose the first time and sovled it the second so i got "You guessed it in 2 tries!"
 - *Extra credit:* open main10.py. Add a comment to each line describing what it is doing (a comment follows a pound sign [#]).
 - *Extra credit:* open main11.py. What is happening on lines 6-11?
  


The grading criteria will be as follows:
 
[1 point] Repository contains a description of the project in README.md

1 point will be awarded for answering the questions associated with each of the files

10 points total (+2 points extra credit)
