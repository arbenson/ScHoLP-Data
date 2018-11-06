This dataset is derived from tags on Stack Overflow posts. The raw data was
downloaded from
https://archive.org/details/stackexchange

Each simplex corresponds to all of the tags used in a post, and each node in a
simplex corresponds to a tag. The times are the time of the post in millisecond
but normalized so that the earliest tag starts at 0.

The file tags-stack-overflow-node-labels.txt maps integer tag ids and the actual tags.

The file tags-stack-overflow-simplex-labels.txt contains the post id for each simplex.
