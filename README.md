
# E02a-Control-Structures

These are my answers to the questions for the assignment.

- Open main01.py. Before running it, what do you expect this program to do?
I expected it to greet me and ask what my favorite color is.
  - Now right click on the main1.py window and select “Run Python File in Terminal”. Click in the bottom panel, and answer the question. Describe what happened. It said greetings and then asked me what my favorite color is.
  - What do you think the program did with what you typed in answer to the question? Nothing 
- Open main02.py. Before running it, describe how this is different than main01.py. This one has an extra command that says print(color) 
  - What do you think the color = input() will do? It will make it say what color I answered the question with.
  - Run the program in the terminal and answer the question. Did the program do what you expected? Yes
- Open main03.py. Before running it, describe how this is different than main02.py. It has more commands in it. There is now if commands and what the computer has to say when one of those commands is met.
  - What is happening on lines 9–12? In 9-12 we have the if statements that should cause the computer to give me different responses based on how I nnswer the favorite color question.
  - Why are lines 10 and 12 indented? Because they are connected to the previous line. So, 10 will do something when line 9 is activated.
  - Run the program and answer the question. What happens if you don’t capitalize Red? It says it is incorrect.
  - What does this tell you about "color"? That it is case sensitive.
- Open main04.py. Before running it, describe how this is different than main03.py. It now has commands to acknowledge Red and red are both correct.
  - What problem is this trying to solve? This is trying to solve the case sensitivity.
  - Run the program and answer the question. What happens if you use some other capitalization scheme (i.e., “RED” or “reD“)? It says that it is incorrect
- Open main05.py. What do you expect line 9 to do? No idea
  - What problem is it trying to solve? it seems like it might be trying to solve any issue with capital letters.
  - Run the program and answer the question. What happens if you add spaces before or after the word (i.e., “ RED “ or “ red”)? It says it is incorrect.
 - Open main06.py. How is line 9 different than in main05.py? It has a new command put in .stand
   - What would you guess .strip() is doing? Possibly to help with the spacing issue.
   - Run the program and answer the question. Is there another way of writing “red” that will break this logic? I suppose you could use the number 3 to instead of the letter e or there could be spaces between each letter.
 - Open main07.py. Before running this program, how do you expect this to be different than main06.py? I expect I can now answer pink or red as my answer.
   - What is happening on line 12? an elif command has been put on that line to interact with the if command on line 10.
   - Run the program and answer the question. 
 - Open main08.py. What is the purpose of line 9? To let me keep picking colors until I pick red.
   - Why are lines 10–17 indented? Because they are all connected to the while command on line 9.
   - Run the program. What would happen if line 10 were moved before line 9 (and no longer indented)? I do not know.
   - Make that change and run the program again. (To end any Python program, you can type ctrl-c)
 - Open main09.py. What is happening on line 13? It has added another command called count
   - What is the purpose of “count”? It tracks how many times an action was performed.
   - What is happening on line 22? It has a command that will make it tell you how many times you tried to answer the question before getting it right.
   - Run the program.
