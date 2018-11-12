# fai VRM Data

## Data format

### swda-data-post_X.csv
```
[WORD/POS] ... [DOES_SENTENCE_START_WITH_I (0 or 1)] [NUM_OF_WORDS] [IS_SPEAKER_SAME_WITH_PREV] 
```

Each conversation can be distinguished by a line with an empty string

### swda-data-post_y.csv
- Disclosure (d)
- Edification (e)
- Acknowledgement (k)
- Rest (x)

This file contains categories of the sentences in `swda-data-post_X.csv`

Each conversation can be distinguished by a line with an empty string

### Dicts
`swda-data-pos_dict.txt` contains kinds of POS words

`swda-data-y_dict.txt` contains kinds of VRM categories