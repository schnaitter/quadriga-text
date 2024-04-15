# Comments by Hannes Schnaitter

I used the following commands to install the requirements:
```bash
$ conda create -p conda python=3.12
$ conda activate ./conda
$ pip install -r requirements.txt
```
Currently `matplotlib` is not installed via `requirements.txt`, therfore we need to run:
```bash
$ pip install matplotlib
```

## file `data-input/FS_1_MVP_Data_Input_Homogenisation.ipynb`
### section 1
- "*keep* structured XML/HTML markup …"
  - Should this be expounded upon? When? More text or maybe links to this use-case?
  - Is it important to know, when to use which format? Is this a learning outcome?
### section 2
- Information about installation procedures (or links to resources). How to use the `requirements.txt`? Which method of presenting installation requirements is the best/preferred? Why?
#### section 2.1
- is simply showing the ocr step enough?
- <b><em>errors</em></b>:
  - how to install the model `frk`? Doesn't seem to be installed via `(venv) $ pip install -r reqirements.txt`
  - `pdftoppm` also doesn't install via the `requirements.txt` file.
  - 

## file `nlp-enrichment/NLP-Enrichment.ipynb`
- everything seems to run after installing the `requirements.txt`.
- it might be a good idea to preface the corpus-annotation in 3.3 with a warning about the time it takes. 


## file `word_search/FS_1_MVP_ANalysis_Prototype_101.ipynb`
- `matplotlib` is not part of `requirements.txt`.
- 
