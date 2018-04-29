# Character-Level-Rnn-Spellerror

###  Purpose
* Use character-level seq2seq model to correct spell error.

### How to use it
* Our trained model is here https://drive.google.com/open?id=1oEjmTUSRTCDtXTCczyFvV4YkdFunSoWu
* LM_and_ch_OpenNMT.ipynb this code use LM to detect sentence error.
* When detecting spell error, our model will give this error five better candidate and then we use LM to find the best answer.
* count_1edit.txt : Counts for all single-edit spelling correction edits
* lab4.confusables.txt : A collection of "right: wrong1, wrong2" spelling mistakes,
* lab4.test.1.txt : Testing data

### Data
* EFCAMDAT from University of Cambridge


### Model
* Use OpenNMT to train seq2seq model







