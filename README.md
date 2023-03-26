
# Text2MCQ using BERT-WSD and T5 Transfomer(Ongoing)

According to various researchers, active recall(retrieval method of studying) has been found effective for better understanding of the study materials. This project is based around the same premise.

Given an input text(eg. paragraph), this model generates Multiple Choice Questions(MCQs) which allows the learners to test their understanding of the subject material.




## Roadmap

- Use abstractive and/or extractive summarization to find important sentences from a paragraph.

- Find keyword/s from the sentences.

- Distractors generation using WordNet and BERT-WSD. Optimally three distractors are generated.

- Generate question using the T5 Transfomer model.

## Tasks Completed

- [ ]  Found important sentences from the pararaph.
- [ ]  Found the keyword/s from the sentence.
- [x]  Found the contextual meaning of the word in a sentence(using pretrained BERT model). 
- [x]  Generated distractors from WordNet for wrong choices.
- [ ]  Generated questions using T5 transformer model.
