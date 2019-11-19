# A Small Challenge with The Shortcut



## Table of Contents
1. [Goal](#goal)
2. [Problems](#problems)
3. [Result](#result)
4. [Acknowledgements](#acknowledgements)

<a name="goal"></a>

## Goal
The purpose of this repository is to answer the questions given by The Shortcut. The questions are about to check the knowledge of Numpy and Pandas, which are basic Python data stack. 

<a name="problems"></a>

## Problems
The original file can be accessed [here](https://github.com/dalpengholic/small_challenge_with_TheShortcut/blob/master/challenges.pdf).
### Input Data
- Numpy 2d array (shape (6x10))
- Pandas dataframe (shape (93x5))

<a name="result"></a>

## Result

The answers can be checked [here](https://github.com/dalpengholic/small_challenge_with_TheShortcut/blob/master/small_challenge.ipynb).

The order of answers are as follows.
1) Numpy 
  - After Refactoring
  - Before Refactoring
  
The best answer is achieved using a Numpy function `np.bincount`. The performance was checked using `%%timeit`.
  
2) Pandas
  - After Refactoring
  - Before Refactoring

First, replace NaNs with "missing". Second, create index using combined values in three columns.

If it is not available to see at GitHub, go to `https://nbviewer.jupyter.org` and paste the address as follows.

`https://github.com/dalpengholic/small_challenge_with_TheShortcut/blob/master/small_challenge.ipynb`

<a name="acknowledgements"></a>

## Acknowledgements
This project is given by [The Shortcut](https://theshortcut.org). 
