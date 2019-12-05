Text matching models on LCQMC datasets

## Requrement
- python 3.6
- tensorflow-gpu 1.12
- gensim 3.8.1
- jieba 0.39
- numpy 1.16
- pandas 0.23

## To Do List
### Single Model
- [x] DSSM
- [x] ABCNN
- [x] ESIM
- [ ] BIMPM
- [ ] DIIN
- [ ] DRCN
- [ ] RE2
### Classic Algorithm
- [ ] TFIDF
- [ ] BM25
- [ ] VSM
### LM Fintune
- [ ] ELMo
- [ ] BERT
- [ ] ALBERT

## Result
Model| accuracy | loss | word/char 
:-: | :-: | :-: | :-: | 
DSSM | 63.336% |  0.64119714  | char
ABCNN | 79.928% | 0.6421789 |  char
ESIM | 81.8% | 0.48200694 |  char
BIMPM |  |  |  
DIIN | 84.472% | 0.34605518 |  char + dynamic word
DRCN |  |  |  
RE2 |  |  |  
