# Alpaca-family-library
Summarize all low-cost replication methods for Chatgpt countiously. It is believed that with the improvement of data and model fine-tuning techniques, small models suitable for various segmented fields will continue to emerge and have better performance.

## What’s Alpaca

 Alpaca project aims to build and share an instruction-following LLaMA model. 

- Github Page: https://github.com/tatsu-lab/stanford_alpaca
- Blog Post: https://crfm.stanford.edu/2023/03/13/alpaca.html

The repo contains:

- The [52K data](https://github.com/tatsu-lab/stanford_alpaca#data-release) used for fine-tuning the model.
- The code for [generating the data](https://github.com/tatsu-lab/stanford_alpaca#data-generation-process).
- The code for [fine-tuning the model](https://github.com/tatsu-lab/stanford_alpaca#fine-tuning).

![Stanford-Alpaca](./assets/logo.png)

The current Alpaca model is fine-tuned from a 7B LLaMA model [1] on 52K instruction-following data generated by the techniques in the Self-Instruct [2] paper, with some modifications that we discuss in the next section. In a preliminary human evaluation, we found that the Alpaca 7B model behaves similarly to the `text-davinci-003` model on the Self-Instruct instruction-following evaluation suite [2].

[1]: LLaMA: Open and Efficient Foundation Language Models. Hugo Touvron, Thibaut Lavril, Gautier Izacard, Xavier Martinet, Marie-Anne Lachaux, Timothée Lacroix, Baptiste Rozière, Naman Goyal, Eric Hambro, Faisal Azhar, Aurelien Rodriguez, Armand Joulin, Edouard Grave, Guillaume Lample. https://arxiv.org/abs/2302.13971v1

[2]: Self-Instruct: Aligning Language Model with Self Generated Instructions. Yizhong Wang, Yeganeh Kordi, Swaroop Mishra, Alisa Liu, Noah A. Smith, Daniel Khashabi, Hannaneh Hajishirzi. https://arxiv.org/abs/2212.10560

## Other models fine-tuned based on the Alpaca model.
