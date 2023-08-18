# beyond-the-surface-vqg
Code and Sample Data for the Paper: "Beyond the Surface: Comprehending the Video's Essence or Merely Glimpsing its Facade? Generating Questions from Videos"
## Requirements
- conda create -n vqg python=3.8.5
- conda activate vqg
- pip install -r requirement.txt
- pip install openai [_only if you want to run the gpt3_5_summariser code_]


## GitHub Repository Contents:
- **Code Implementations:** The "_bart_Ce.py_" file contains BART implementation with Cross Entropy loss.  The "_bart_CntCe.py_" file contains code for BART fine-tuning with Contrastive + Cross Entropy loss. The "_t5_Ce.py_" file is for fine-tuning the T5-base model with Cross Entropy loss, and the "_t5_CntCe.py_" file contains T5-base implementation with Contrastive + Cross Entropy loss. The "_gpt3_5_summariser.py_" file holds the code to generate summaries from the gpt-3.5-turbo model, and the "_bert_classifier.py_" implements our BERT-based classifier.
- **Dataset:** We provide a sample of our dataset in the "_sample_data.xlsx_" file.
