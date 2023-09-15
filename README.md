# Android Project 1 - Wordini

Submitted by: Christopher Joyce

Wordini is an android app that recreates a simple version of the popular word game [Wordle](https://www.nytimes.com/games/wordle/index.html). 

Time spent: 1.5 hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] **User has 3 chances to guess a random 4 letter word**
- [x] **After 3 guesses, user should no longer be able to submit another guess**
- [x] **After each guess, user sees the "correctness" of the guess**
- [x] **After all guesses are taken, user can see the target word displayed**

The following **optional** features are implemented:

- [ ] User can toggle betweeen different word lists
- [ ] User can see the 'correctness' of their guess through colors on the word 
- [ ] User sees a visual change after guessing the correct word
- [ ] User can tap a 'Reset' button to get a new word and clear previous guesses
- [x] User will get an error message if they input an invalid guess
- [ ] User can see a 'streak' record of how many words they've guessed correctly.

The following **additional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

The first GIF shows a user submitting a guess, attempting to submit invalid guesses (not 4 letters), then getting the answer correct by the second guess.

![wordiniSuccess](https://github.com/cjj22NJIT/WordleCJJ22/assets/144167084/eaf24aeb-3470-42fc-a163-26215d1d1925)

The second GIF shows a user incorrectly guessing three times and then attempting to guess a fourth time.

![wordiniIncorrect](https://github.com/cjj22NJIT/WordleCJJ22/assets/144167084/1faa3f48-a797-48b4-b73d-928ba78a5020)


GIF created with ScreenToGif  


## Notes

No major challenges encountered. App makes a Toast pop up when a word that isn't 4 letters in length is submitted.
App no longer accepts answers after three guesses.
Guess input box clears itself on submit.
