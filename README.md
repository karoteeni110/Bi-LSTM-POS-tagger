## Intro

This project is focusing on POS tagging problem. 

It is a course project for Introduction to Deep Learning course under Digital Humanities Department of University of Helsinki. Referring to Plank et al. (2016), I implemented 18 Bi-LSTM tagging models for labeling Finnish (fi), German (de) and Swedish.

Factors explored here include 1) loss function and 2) representation setting. For more information, see `DL_2020_Final_Project.pdf`.

## Usage

The code can be reused to train models.

- For model with auxilary loss: 

	`python3 auxloss_model.py`
	
- For model with NO auxilary loss:

	`python3 no_auxlooss_model.py`
	
- For the most-frequent-baseline model:

	`python3 most-freq_baseline.py`
	
- To change over languages, modify the filepaths to datasets:

	Change `TRAIN_FPATH`, `TEST_FPATH`, `DEV_FPATH` in `data_ud.py`
