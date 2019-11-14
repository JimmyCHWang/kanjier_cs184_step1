## Description

This repository is for the UCSC CSE184 F19 final project, step 1. 

As part of the Kanjier group, this piece of code is intended to scrape the most frequently used 2,136 kanjis, from the Wikipedia page " [https://en.wikipedia.org/wiki/List_of_j%C5%8Dy%C5%8D_kanji](https://en.wikipedia.org/wiki/List_of_jōyō_kanji) ", which is based on an official document from Agency of Cultural Affairs, Government of Japan (http://www.bunka.go.jp/kokugo_nihongo/sisaku/joho/joho/kijun/naikaku/pdf/joyokanjihyo_20101130.pdf).

Running the code will create a csv file "kanji_list.csv" in the same directory as the `.ipynb` file.
The csv file has header. The data frame has 2,136 rows (index from 1 to 2,136) and 2 columns "index" which is their index, and "kanji" which are the individual kanji characters.

## Usage

### Environment

You are required to have `Python 3.7` environment, with the following packages installed:

```
ipython
jupyter
bs4
numpy
pandas
```



### Generate csv file

Use jupyter notebook to open the `.ipynb` file and run all.

### Read the csv file

To read the csv file, use:

```python
import pandas as pd
container = pd.read_csv('kanji_list.csv')
```

You'll get a 2136x2 data frame described as above.



