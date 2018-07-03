Reaching Human-level Performance in Automatic Grammatical Error Correction: An Empirical Study
===============================================================================================

This repository contains our systems' outputs for CoNLL-2014 and JFLEG test set.

The repository is organized as follows:

    .
	©À©¤©¤ system_outputs
	©¦	©À©¤©¤ conll      # system outputs on CoNLL-2014 test set
	©¦	©¦   ©À©¤©¤ conll_base.txt	# base convolutional seq2seq model's outputs
	©¦	©¦	©À©¤©¤ conll_fb_learning.txt	# base + fluency boost learning
	©¦	©¦   ©¸©¤©¤ conll_fb.txt	# base + fluency boost learning and inference
	©¦	©¸©¤©¤ jfleg      # system outputs on JFLEG test set
	©¦	    ©À©¤©¤ jfleg_base.txt	# base convolutional seq2seq model's outputs
	©¦		©À©¤©¤ jfleg_fb_learning.txt	# base + fluency boost learning
	©¦	    ©¸©¤©¤ jfleg_fb.txt	# base + fluency boost learning and inference
	©¸©¤©¤ README.md
	
	
Performance

| System                     | CoNLL-2014 | CoNLL-10 | CoNLL-10 (SvH) | JFLEG |
| :--- | --- | --- | --- | --- |
|Base convoluational seq2seq | 57.95 | 73.19 | 72.28 | 60.87 |
|Base + FB learning | 61.34 | 76.88 | 75.93 | 61.41 |
|Base + FB learning and inference | 60.00 | 75.72 | 74.84 | 62.42 |
|Human Peformance|  - | - | 72.58 | 62.37 |


Please refer to the following paper if you want to use/study the results:

Tao Ge, Furu Wei, Ming Zhou: Reaching Human-level Performance in Automatic Grammatical Error Correction: An Empirical Study. arxiv.org