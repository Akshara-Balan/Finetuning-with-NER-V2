# Finetuning with NER V2

The repository contains my second attempt to finetune a BERT model.

Here I finetuned a Malayalam BERT model: __l3cube-pune/malayalam-bert__

For that first I extracted 50000 data of malayalam NER from __'ai4bharat/naamapadam', 'ml'__ and uploaded it to my huggingface profile as __AksharaBalan/malayalam-ner-dataset-naamapadam__.

Later I finetuned malayalam BERT using that dataset for 3 epochs.
