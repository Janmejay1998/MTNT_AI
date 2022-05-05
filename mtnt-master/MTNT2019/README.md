WMT 2019 Shared Task: Machine Translation Robustness: blind test files
======================================================================

This archive contains 4 files:

    en-fr.final.tsv
    en-ja.final.tsv
    fr-en.final.tsv
    ja-en.final.tsv

Each file is tab separated with 4 columns:

1. The first column is a unique number identifying each sentence
2. The second column is a number identifying **comments**. Some sentences come from the same reddit comments. Sentences are ordered as they were found in each comment.  Should you want to, you may use this information to leverage context from sentences that come from the same comment.
3. The third column contains the source sentence.
3. The fourth and last column contains the reference translation.

If you have any question, feel free to contact the shared task organizer at wmt-tasks@googlegroups.com