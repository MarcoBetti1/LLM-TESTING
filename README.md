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


