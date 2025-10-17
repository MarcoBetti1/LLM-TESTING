# LLM-TESTING
Organize different llm benchmark ideas

What is Intelligence?
Solving of problems correctly? efficiently?
Logic?

What does this all even mean?

LLMs can produce useful output buy predicting the next tokens. While one might boil down the complexity to predicting the end of a setence, or the next two sentences. No one can truly define the limit of the complex problem solving that can be achieved by using these sentence predictors in different ways.

When you use chatgpt.com or most other mainstream llm providers chat sites, you are not interacting with an llm. You are interacting with a system of llm prompts and responses. While the input and output are in the same format as interacting directly with an llm, the quality of the response is much higher from these systems. 

Lets say I created program X that could predict the response of any prompt with 90% accuracy. 90% is pretty good, but what If I changed the program so after it outputs an answer, it will input that answer and a new question "is this the right answer". Will my accuracy increase? I have 90% confidence its correct, but I then layer on a 90% confidence answer check. In the case of the 90, where my answer is right. There is only a 10% the answer check says its wrong (since it is correct and program X has 90% accuracy). And in the case of the 10 (where the answer is wrong), there is only a 10% chance that the wrong answer is incorrectly flagged as correct.

First run correct: 90% of happening. 90% of marking correct, 10% of marking incorrect.
First run incorrect: 10% of happening. 90% of marking correct, 10% of marking incorrect.

This actually decreases overall answer accuracy? What am I even trying to say here?


## Classic intelligence
For a decent portion of recent history, the game of chess has been remarked as some quantifier of intelligence. Chess requires knowledge of a large rule set, but even more importantly, it involves logical analysis and prediction of a game state. One must evaluate their opponents best moves, one, two, three or more turns in the future. Then use this predictive analysis to decide their current best move. While chess is extremely complex, it can be solveable. It was only until recently that a chess engine using AI was able to beat the best human player. It wont be long until a chess program using only llm reasoning will beat the best engine.


https://github.com/MarcoBetti1/llmchess

## Human-like attention
Us humans have the ability to pick and choose where we put our attention. We can abstract details in real time, and understand what level of complexity is best to use our reasoning on. Lets say you are playing the matching game where you turn 2 cards and see if they match. When you flip one and get it wrong, you remember some unique thing about that card, and something about its position. This way if you see the matching card you will remember where the original one was. When you flip over a second card that isnt matching, you may forget entirely where that is. You decided that your attention needs to remain on the card that you know where it is. LLMs cannot do this. They treat every input token as an equal part of the prompt. At what point will an LLM get confused between instructional prompt, and irrelevant jargon?

https://github.com/MarcoBetti1/FTAAT
