# nlp_knowledge_bases

Knowledge Bases and Dictionaries for NLP++. Dictionaries folder contains all .dict files, while kb folder contains all .kbb files.

### Contents

##### icd9_code_2_words.kbb
 - Maps icd9 nine codes to keywords contained in its long title. A list of stopwords has been filtered out.

##### radlex_word_tree.kbb 
 - A tree where each path from root to leaf constitutes a valid radlex term.

##### radlex_labels_and_phrases.kbb
 - Raw list of radlex terms and codes.
 
##### specialist_lexicon.dict
 - Dictionary with all single-word, alpha-only entries in the specialist lexicon. 
 - Attributes include of pos, abbreviations, acronyms, and spelling variants.
 - All attributes consisting of a list of items are comma separated. 
