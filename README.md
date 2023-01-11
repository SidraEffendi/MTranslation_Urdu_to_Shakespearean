# MTranslation_Urdu_to_Shakespearean

Goal:

Translating Udru poetry to Shakespearean English

Methodology:

- Trained a pre-trained Helsinki model on Bible and Quran Urdu-English parallel to translate Urdu to Modern English (Pivot language).
- After zero-shot translation of Urdu poetry to Modern English, fine-tuned Shakespeare GPT-2 model to get output in Shakespearean English.

<img width="458" alt="Screenshot 2022-04-21 at 7 58 02 PM" src="https://user-images.githubusercontent.com/5307694/189572190-3c5af5dd-446d-427b-9cbc-47ca1ae9b068.png">


Reasources:

Used University of Michigan, Ann Abor computing cloud gpu service to train the models. The trained models are here- https://drive.google.com/drive/folders/1Nd9KFbgLXVmNgcG5tUmOVOPvLGarNo1V?usp=sharing

Replicate:

To try other Urdu poems or text just download the two trained models from the google drive and the notebook on your machine and hit run.

Scope of Improvement:
- The Urdu to English translation model was trained on Bible and Quran Parallel corpus, so the poetic translation can be improved by using 
a parallel corpus of Urdu poetry to Modern English or vice-versa.
- due to memory constraints on the machine we could not experiment with models like mBert50 but anticipate the BLEU score will be higher for it.

