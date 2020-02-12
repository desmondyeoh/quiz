# Quiz App (desmondyeoh/quiz)
This is a minimalistic quiz application that reads from text files.
Demo: [http://dyeoh.com/quiz](http://dyeoh.com/quiz)
- Tap on the question to reveal the answer

## How to use?
1. Put questions and answers in a `SUBJECT_NAME.txt` file. 
Note that:
* There should be 1 line between the question and the answer. 
* There should be 2 lines between the question-and-answer pairs.
* Example:
```
What is the color of the sky?

Blue


What is the color of the blood?

Red
```

2. Put the `SUBJECT_NAME.txt` in `data/` folder.

3. Add the following line inside the element `<div id="menuScreen">`, in `index.html`.
```
<button class="subject" data-filename="SUBJECT_NAME.txt">SUBJECT_NAME</button>
```
