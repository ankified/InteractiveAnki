# InteractiveAnki
<img src="https://i.ibb.co/NNX2Vjh/custom-Template.png" alt="custom-Template" border="0">
<img src="https://i.ibb.co/5GmBrHf/custom-Template-Back.png" alt="custom-Template-Back" border="0">
<img src="https://i.ibb.co/HV49RNq/custom-Template-Back2.png" alt="custom-Template-Back2" border="0">
<img src="https://i.ibb.co/987Fp7P/memrise-Template.png" alt="memrise-Template" border="0">
<img src="https://i.ibb.co/2gv9n8g/memrise-Template-Back.png" alt="memrise-Template-Back" border="0">
<img src="https://i.ibb.co/f0kmvys/memrise-Template-Back2.png" alt="memrise-Template-Back2" border="0">
<img src="https://i.ibb.co/mDgr7wy/truefalse.png" alt="truefalse" border="0">


Hi,

I made these interactive MCQs and interactive True/False using Javascript (meaning it's also compatible with ankidroid).
The Javascript, the HTML and the CSS are all easy to read and modify.

It contains 5 note types:
1) Interactive - MCQ custom: this uses a custom MCQ template, the questions will always be asked in the same order in which you wrote them.
2) Interactive - MCQ custom shuffled: this uses a custom MCQ template, the questions will be shuffled around each time.
3) Interactive - MCQ Memrise: this uses a Memrise-like template, the questions will always be asked in the same order in which you wrote them.
4) Interactive - MCQ Memrise shuffled: this uses a Memrise-like template, the questions will be shuffled around each time.
5) Interactive - True False
___________________________

How to create cards:

You can add up to 9 options, but I've only put fields for 4 in the examples. You can just add fields called "Option5", "Option6", etc.
If only one answer will be correct, just write the number of the answer in the "Answer" field. For example, if the 3rd option is right, just type "3" in the "Answer" field. The card will flip automatically and show you if your answer was correct once you click on an option.

<img src="https://i.ibb.co/fQq9jBB/single-Answer.png" alt="single-Answer" border="0">

If there are multiple correct answers or if you don't want the card to flip automatically, type "1" for each right choice and "0" for each wrong choice in order. For example, type "1010" to indicate that the 1st is correct, the 2nd is wrong, the 3rd is correct and the 4th is wrong.

<img src="https://i.ibb.co/tqQBYKm/multiple-Answers.png" alt="multiple-Answers" border="0">

For the True/False, type "1" or "t" in the answer field if it's true, leave the answer field blank if it's false.
