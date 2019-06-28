# Text Preprocessing

Songsheng Ying, 2019.

This is a sub repository of 
***
**Similarity and Association:**

Principles of Distributed Semantic Processing in the Human Brain, 
***
a research project conducted within the Cogmaster M2 research internship.

**Author:** 
Songsheng Ying, soshyng@gmail.com

**Supervisors:** 
Sabine Ploux, Laurent Bonnasse-Gahot, Christophe Pallier.
***

## About Micipsa

Micipsa is the code named for the research internship project mentioned above. 
It investigates the two aspects of semantic processing's implication in the human brain. 

[Root repository of Micipsa](https://github.com/nicolasying/micipsa.github.io)

[Masters' thesis](https://github.com/nicolasying/Micipsa-Thesis)

## File Structure

### Text Pre Processing ipynb

Perform LPP text lemmatization with `spacy`'s syntax parser and `FrenchLefffLemmatizer`.

### LPP/Lemmatisation Feature Gen 

Load lemmatised LPP onset file with POS information into the LPP folder, then the notebook converts the lemma onsets to semantic activations given semantic spaces in `word2vec` format.

