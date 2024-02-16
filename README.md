# NIMZ-at-SemEval-Task-9-BRAINTEASER

# This project is about:
Answering multiple-choice riddle-like questions, regarding the SemEval2024-Task-9-BRAINTEASER, which includes two subtasks: Sentence Puzzle and Word Puzzle.
We have trained and evaluated BERT-Base and RoBERTa-Large LMs, T5-Large and QA-GNN on the BRAINTEASER task dataset.

## About the notebooks in this repository:
- **BERT_base_Sentence_Puzzle_Eval_phase.ipynb**: The notebook for training BERT_base for Sentence Puzzle subtask.
- **BERT_base_Word_Puzzle_Eval_phase.ipynb**: The notebook for training BERT_base for Word Puzzle subtask.
- **RoBERTa_Large_Sentence_Puzzle_Post_Eval_phase.ipynb**: The notebook for training RoBERTa_large for Sentence Puzzle subtask.
- **RoBERTa_Large_Word_Puzzle_Post_Eval_phase.ipynb**: The notebook for training RoBERTa_large for Word Puzzle subtask.
- **T5_large_sentence_puzzle_v1.ipynb**: The notebook for training T5_large for Sentence Puzzle subtask.
- **T5_large_word_puzzle_v1.ipynb**: The notebook for training T5_large for Word Puzzle subtask.
- **QA_GNN_brainTeaser_v14.ipynb**: The notebook for training QA-GNN for Word Puzzle and Sentence Puzzle subtasks.


## Saved Models Links:
### BERT_base_Sentence_Puzzle: *https://drive.google.com/drive/folders/1AkrL6ys_SPuVI3iydk7JUTpkeLSSr7Zs?usp=sharing*

### BERT_base_Word_Puzzle: *https://drive.google.com/drive/folders/10VycHTNnuTyt9AkuNaiTmrcWTlSO4Rre?usp=sharing*

### RoBERTa_Large_Sentence_Puzzle: *https://drive.google.com/drive/folders/1uWTGFERtmT895GvKQ4mqZ8iEMCvB0wdw?usp=sharing*

### RoBERTa_Large_Word_Puzzle: *https://drive.google.com/drive/folders/1s7kPs_ZP2UJWcr5ZharSAgtNdj0-6hdR?usp=sharing*

### T5_large_sentence_puzzle: *https://drive.google.com/drive/folders/1-iOgEsA2ZdZj3nyram2TCHd9iSSX7NeW?usp=sharing*

### T5_large_word_puzzle: *https://drive.google.com/drive/folders/1Xxx7LPjHjQhDFd1KvfMFgjVXMuJ_ChHf?usp=sharing*

### QA-GNN_sentence_puzzle: *https://drive.google.com/drive/folders/1edmQxKagLplvdpcYCmBal5Cl7hB0KcqQ?usp=sharing*

### QA-GNN_word_puzzle: *https://drive.google.com/drive/folders/1J7CRJRnTY6rrkcfwHsBkXvptxuHiMvFf?usp=sharing*


## Data Information:
- **BRAINTEASER_dataset folder**: contains the original BRAINTEASER task dataset.


---------------------------------------
## Dataset Examples:

| task | column_name | column_value |
|----------|----------|-------------------------------------------------------------------|
| PG    | SRC| The budget cannot be adopted against the will of the European Parliament.|
|          | HYP|  The European Parliament does not approve the budget. |
|          | Label| Not Hallucination|
| DM    | SRC| Communistic birds. What is the meaning of communistic? |
|          | TGT| Living or having their nests in common. |
|          | HYP|Of or pertaining to communism. |
|          | Label| Hallucination|


------------------

## Contributors
- Zahra Rahimi: [Linkedin](https://www.linkedin.com/in/zahra-rahimi-7a089115b/), [Github](https://github.com/z-rahimi-r)
- Mohammad Moein Shirzady: [Linkedin](https://www.linkedin.com/in/shirzady/), [Github](https://github.com/shirzady1934)



