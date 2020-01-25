
# E02a-Control-Structures

- Open main01.py. Before running it, what do you expect this program to do?
    I expect it to ask what my favorite color is.
  - Now right click on the main1.py window and select “Run Python File in Terminal”. Click in the bottom panel, and answer the question. Describe what happened.
    It greeted me then asked my favorite color. I answered and nothing happened.
  - What do you think the program did with what you typed in answer to the question?
    All that it as programmed to do was ask what my favorite color was.

- Open main02.py. Before running it, describe how this is different than main01.py.
    It is different because it has a third line of code.
  - What do you think the color = input() will do?
    Answer with the color I say.
  - Run the program in the terminal and answer the question. Did the program do what you expected?
    Yes. I answered orange and it replied with orange.

- Open main03.py. Before running it, describe how this is different than main02.py.
  - What is happening on lines 9–12?
      It is programmed to have the player guess a color and if they reply with red it will say correct and if they don't say red it will say sorry try again.
  - Why are lines 10 and 12 indented?
      They are the directions for what the program will do after the player inputs. 
  - Run the program and answer the question. What happens if you don’t capitalize Red?
      If you type in red, it will say you got it wrong. 
  - What does this tell you about "color"?
      If you use the command color, it will always has to be specified with "red" and "Red". 

- Open main04.py. Before running it, describe how this is different than main03.py.
      It specified "Red" and "red".
  - What problem is this trying to solve?
      It's solving the problem that the player will run into when not capitalizing letters. 
  - Run the program and answer the question. What happens if you use some other capitalization scheme (i.e., “RED” or “reD“)?
      The player will get it wrong if they answer with any other capitalization scheme.

- Open main05.py. What do you expect line 9 to do?
    I'm not sure what to expect with using lower.
  - What problem is it trying to solve?
    I'm assuming it's going to solve the capitalization scheme issue.
  - Run the program and answer the question. What happens if you add spaces before or after the word (i.e., “ RED “ or “ red”)?
    It doesn't work. It says you got it wrong. 

 - Open main06.py. How is line 9 different than in main05.py?
    It has the word strip added.
   - What would you guess .strip() is doing?
    I would guess it's going to elimate the spacing problems.
   - Run the program and answer the question. Is there another way of writing “red” that will break this logic?
    Yes, I typed " r e D " and it say I got it wrong.

 - Open main07.py. Before running this program, how do you expect this to be different than main06.py?
    This is different because they used another command for the color pink, describing it as "close".
   - What is happening on line 12?
    Addressing the issue if some player guesses "pink".
   - Run the program and answer the question.

 - Open main08.py. What is the purpose of line 9?
    To give us the answer.
   - Why are lines 10–17 indented?
    They correspond to the answer, which is red. 
   - Run the program. What would happen if line 10 were moved before line 9 (and no longer indented)?
    It lets you keep guessing before the game is over until you get it right. 
   - Make that change and run the program again. (To end any Python program, you can type ctrl-c)

 - Open main09.py. What is happening on line 13?
   - What is the purpose of “count”?
    It keeps track of how many times the player guesses. 
   - What is happening on line 22?
    There's no line 22. 
   - Run the program.

 - *Extra credit:* open main10.py. Add a comment to each line describing what it is doing (a comment follows a pound sign [#]).
 - *Extra credit:* open main11.py. What is happening on lines 6-11?
  
 