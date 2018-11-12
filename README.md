# fai VRM Data

## Data format

### swda-data-post_X.csv
```
[WORD/POS] ... [DOES_SENTENCE_START_WITH_I (0 or 1)] [NUM_OF_WORDS] [IS_SPEAKER_SAME_WITH_PREV] 
```

Each conversation is divided by a line with an empty string

### swda-data-post_y.csv
This file contains a category of the sentence in `swda-data-post_X.csv`

The categories are:
- Disclosure (d)
- Edification (e)
- Acknowledgement (k)
- Rest (x)

Each conversation is divided by a line with an empty string

### Dicts
`swda-data-pos_dict.txt` contains kinds of POS words

`swda-data-y_dict.txt` contains kinds of VRM categories