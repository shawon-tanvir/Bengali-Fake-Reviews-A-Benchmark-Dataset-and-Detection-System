# Bengali Fake Reviews: A Benchmark Dataset and Detection System
This paper introduces the Bengali Fake Review Detection (BFRD) dataset, the first publicly 
available dataset for identifying fake reviews in Bengali. The dataset consists of 7710 non-fake 
and 1339 fake food-related reviews collected from social media posts. To convert non-Bengali 
words in a review a unique pipeline has been proposed that translates English words to their 
corresponding Bengali meaning and also back transliterates Romanized Bengali to Bengali. 
We have conducted rigorous experimentation using multiple deep learning and pre-trained transformer 
language models to develop a reliable detection system. Finally, we propose a weighted ensemble model 
that combines four pre-trained transformers: *BanglaBERT, BanglaBERT Base, BanglaBERT Large* and *BanglaBERT Generator*.

## Repository Structure
The repository has two folders:

Code: All the codes for deep learning models, transformers, ensemble model and text conversion pipeline are available.
Dataset: Contains two excel files (a) fake.xlsx (b) non-fake xlsx
Each file contains two columns: **Review** (collected raw reviews), **Label** (annotations).