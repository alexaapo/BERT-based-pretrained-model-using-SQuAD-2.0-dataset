# BERT based pretrained model using SQuAD 2.0 Dataset for Question-Answering

Here I built a BERT-based model which returns an answer, given a user question and a passage, which includes the answer of the question. For this question answering task, I used the [SQuAD 2.0 dataset](https://rajpurkar.github.io/SQuAD-explorer/).

#### You should read the notebooks with this order:
1. Fine_Tuning_Bert
2. Evaluate_Fine_Tuned_Bert
3. Evaluate_Existed_Fine_Tuned_Bert

I started with the BERT-base pretrained model [bert-base-uncased](https://huggingface.co/bert-base-uncased) and fine-tune it to have a question answering task, implemented by myself.

Then, I evaluate the model with different passages, with increasing difficulty level. 

Finally, as a benchmark I used the implemented pretrained and fine-tuned model from ***Hugging Face***, named as [bert-large-uncased-whole-word-masking-finetuned-squad](https://huggingface.co/bert-large-uncased-whole-word-masking-finetuned-squad). You will see, that my model performance is pretty decent.

***Note:*** My solution is implemented in PyTorch and the report is well documented. For running the notebooks, I used the Google Colab with its GPU.

You can check the Google Colab Notebooks here:
  * Fine Tuned Bert: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1_WLfNcueLY3Clo_xh1RyswbGxNPKKz6f)
  * Evaluate Fine Tuned Bert: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/12QVM3VpQX5BzzDofoSPeVAXoSpzlK_CR)
  * Evaluate Existed Fine Tuning Bert: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1CRNY4_aFulKZgdmMHBCybf7629wPFDsL)
