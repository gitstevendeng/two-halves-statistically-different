# two-halves-statistically-different
Text data and Mathematica codes for the paper "Two halves of a meaningful text are statistically different"

1. Mathematica notebooks
  a. prep-split.nb: tokenization of strings and splitting texts into two halves.
  b. quantities-stats.nb: functions for calculating all quantities in the paper; examples for the 156 text set.
  
  
2. Text data
  I. 156 text set
    a. GutenbergAll: the original 156 texts were retrieved from http://www.gutenberg.org/wiki/Category:Fiction_Bookshelf.
    b. GutenbergAllProc: in cases where texts may contain hidden symbols "^M" due to preparations under Windows system, this folder contains 156 texts with these symbols removed.
    c. GutenbergAllReverse: 156 texts with their word orders inverted.
    d. GutenbergAll_Split: split each files "text" into two halves (text_1.txt and text_2.txt) and tokenize them (texttokens_1.dat and texttokens_2.dat).
    
   
  II. 350 text set
    a. Novels350: the original 350 texts were retrieved from http://novel.tingroom.com/.
    b. Novels350Proc: ...
    c. Novels350Reverse: ...
    d. Novels350_split_1 + Novels350_split_2: Due to size limit on github, the zip file was splitted into two parts.


For any questions concerning the codes, please contact RongRong Xie (emilyxierr@gmail.com) or Shengfeng Deng (gitsteven@gmail.com).
