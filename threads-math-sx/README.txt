This dataset is derived from threads on math Stack Exchange posts. The data was
downloaded from
https://archive.org/details/stackexchange

Each simplex corresponds to a post where the question and all answers to the
question appeared within 24 hours. The nodes in each simplex are the elements of
the set consisting of the users that answered the question and the user that
asked the question.  The times are the time of the post in millisecond but
normalized so that the earliest post starts at 0.

The file threads-math-sx-simplex-labels.txt maps each simplex to the stack
exchange post id.
