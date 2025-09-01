# OSCARPIE
A very large dataset of Potential Idiomatic Expressions from creative commons OSCAR via CommonCrawl. CC0 license @ https://huggingface.co/datasets/oscar-corpus/oscar</br>
Phrases were matched from a combined vocabulary list from EPIE, MAGPIE, LIdioms, and FLUTE. In addition to previous and next sentences, </br>
part of speech, and BIO-lables, BERT output embeddings were acquired and post-processed to provide extra pre-calculate semantic relationships.</br>
This repo is under construction. The data format may also change for clarity. </br> 
The complete collection of files contains 7,713,773 examples of 3209 unique possible idioms. </br>
Without "listen" and "catch", the total remains 6,850,525 with 3207 unique possible idioms.</br>

5 full files will be added to this folder in GoogleDrive. </br>
https://drive.google.com/drive/folders/1Hf4Q0lIAU6a3HlJ4OwDMSLFqb3wLpkwn</br>

Full Dataset Statistics: </br>

**POS totals**: {'CC': 9002327, 'IN': 27459419, 'DT': 22090500, 'NN': 38705636, 'VBG': 4932331, 'NNP': 19458624, 'NNS': 11763956, 'WDT': 1087759, 'VBP': 6393665, 'JJ': 16908873, 'RB': 9984967, ',': 10743258, 'MD': 2750466, 'VB': 10521993, 'PRP$': 3846351, ':': 3242585, '.': 10137900, 'VBZ': 5443694, 'WRB': 1142320, 'CD': 3917295, 'POS': 514308, 'VBD': 5084171, '(': 873140, ')': 897444, 'VBN': 3987065, 'PDT': 410830, 'UH': 51093, 'FW': 100677, 'TO': 7060856, 'PRP': 10671868, 'JJR': 686925, "''": 1084072, 'RP': 1312239, 'SYM': 92732, 'JJS': 584004, 'NNPS': 212719, 'WP': 891184, '#': 63344, 'RBR': 367229, 'RBS': 136472, 'EX': 367994, '$': 137020, 'WP$': 21326, 'LS': 2773, '``': 8299}</br>
  **Avg. phrase length**: 2.70, median: 3</br>
  **Avg. sentence length**: 31.27, median: 26</br>
  **Avg. position ratio**: 0.4796, median: 0.5000</br>
  **Begin-POS counts**: {'VB': 1022087, 'NN': 2530185, 'IN': 2142523, 'PDT': 205702, 'RB': 416518, 'JJ': 507699, 'TO': 155124, 'DT': 322985, 'CD': 35696, 'NNS': 91451, 'WRB': 17465, 'VBG': 78336, 'VBN': 101378, 'VBP': 31915, 'RBR': 4616, 'PRP$': 7947, 'JJR': 12940, 'CC': 13593, 'PRP': 9473, 'EX': 278, 'WP': 929, 'JJS': 3058, 'VBD': 1167, 'UH': 551, 'RP': 57, 'MD': 99, 'VBZ': 1}</br>
  **End-POS counts**: {'NN': 4912962, 'VB': 239957, 'VBD': 67510, 'RB': 170148, 'IN': 664987, 'DT': 102945, 'NNS': 479750, 'RBR': 35607, 'JJ': 502606, 'RP': 240314, 'VBZ': 26660, 'VBG': 78654, 'SYM': 10118, 'PRP': 39183, 'EX': 6139, 'CD': 8989, 'TO': 27807, 'MD': 4271, 'PRP$': 7278, 'JJS': 47676, 'VBP': 25428, 'VBN': 14763, '.': 1, 'POS': 17, 'RBS': 3}
