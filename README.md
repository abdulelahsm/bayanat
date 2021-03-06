
**bayanat** is a simple library for gathering statistics about Arabic text.

## Examples

```python
from bayanat import Bayanat
dataset = Bayanat(path)
```
Arguments

* `get_top_largest_words` retrieves largest words. 
* `sample_words_by_char` sample words by character. 
* `sample_random_sentence` sample a sentence with a given size. 
* `get_freq_of_chars` get all chars and frequency. 
* `get_ratio_of_non_arabic` show percentage of non Arabic chars. 
* `get_ratio_of_english` show percentage of English chars.
* `get_ratio_of_arabic` show percentage of Arabic chars.  
* `get_stats` print number of tokens and lines.  
* `plot_embeddings` given some words it plots the words using embeddings. This sues `AraVec` model. 

## Demo 
Run directly on [Colab](https://colab.research.google.com/github/ARBML/bayanat/blob/main/demo.ipynb). 
## Contribution 
This is an open source project where we encourage contributions from the community. 

## License
[MIT](LICENSE) license. 

## Citation
```
@misc{bayanat2020,
  author = {Zaid Alyafeai and Maged Saeed},
  title = {bayanat: Statistics of Arabic Text.},
  year = {2020},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/ARBML/bayanat}}
}
```



