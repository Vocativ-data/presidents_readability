# Presidential speech grade level #
----------

This data-set takes presidential speeches from the Miller Center (http://millercenter.org/), runs them through three readability algorithms (Flesch reading ease, Flesch-Kincaid grade and SMOG).
We also include a sentence, word, unique word and syllable count (as well as average words per sentence and syllables per word).
Finally, we have for each speech a count of most frequent words (after discounting connector words such as "the," "it," etc.)

Obama speeches not included in the  Miller Center's data-base were manually downloaded from transcripts.

## Note on data ##
Flesch-Kincaid grade scores should correspond with actual grades, such that a 1 is a text easily understood by a first grader, a 12 by a high-school graduate, and a 21 by a PhD holder. In that vein, grade scores lower than 1 or greater than 21 were changed to 1 and 21 (respectively) for ease of interpretation.
