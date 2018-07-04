Reaching Human-level Performance in  
Automatic Grammatical Error Correction:  
An Empirical Study
===============================================================================================

# Introduction

This repository contains our systems' outputs for CoNLL-2014 and JFLEG test set.

The repository is organized as follows:

    .
	├── system_outputs
	│	├── conll      # system outputs on CoNLL-2014 test set
	│	│   ├── conll_base.txt	# outputs of the base convolutional seq2seq model
	│	│   ├── conll_fb_learning.txt	# outputs of base + fluency boost learning
	│	│   └── conll_fb.txt	# outputs of base + fluency boost learning and inference
	│	└── jfleg      # system outputs on JFLEG test set
	│	    ├── jfleg_base.txt	# outputs of base convolutional seq2seq model
	│	    ├── jfleg_fb_learning.txt	# outputs of base + fluency boost learning
	│	    └── jfleg_fb.txt	# outputs of base + fluency boost learning and inference
	└── README.md
	
	
# Performance

| System | CoNLL-2014 | CoNLL-10 | CoNLL-10 (SvH) | JFLEG |
| :--- | :---: | :---: | :---: | :---: |
|Base convoluational seq2seq | 57.95 | 73.19 | 72.28 | 60.87 |
|Base + FB learning | 61.34 | 76.88 | **75.93** | 61.41 |
|Base + FB learning and inference | 60.00 | 75.72 | **74.84** | **62.42** |
|Human Peformance|  - | - | 72.58 | 62.37 |

The results in the CoNLL and JFLEG are Max-match F_{0.5} and GLEU score respectively.

# Reference

Please refer to the following paper if you want to use/study the results:

Tao Ge, Furu Wei, Ming Zhou: Reaching Human-level Performance in Automatic Grammatical Error Correction: An Empirical Study. https://arxiv.org/abs/1807.01270