# LLM_from_scratch_gpt2_small

### Contributors:
Eman Ansar
eansar@andrew.cmu.edu
Carnegie Mellon University

Olabode Ajenifujah
oajenifu@andrew.cmu.edu
Carnegie Mellon University

Siddharth Saha
ssaha3@andrew.cmu.edu
Carnegie Mellon University

Yujie Li
yujiel2@andrew.cmu.edu
Carnegie Mellon University

# Dataset for Pretraining:
The pretraining corpus for the LLM is constructed using a
carefully curated subset of the OpenWebText dataset ensuring
a diverse and representative collection of text source. The Tiny
Shakespeare corpus contains text data serves as the source
for pretraining the language model, where the input is Text
sequences, tokenized at the character level. Each character
is encoded as an integer, and the sequences are batched for
training. For each input sequence, the target output is the
subsequent character sequence, shifted by one position, where
the model learns to predict the next character given the current
sequence.

# Dataset for Finetuning:

SQuAD (Stanford Question Answering Dataset) dataset was
used for the questioning/answering task. The input Context
passages and questions are tokenized and encoded. These
tokenized sequences are concatenated, and special tokens are
inserted to delineate different parts of the input. The output is
the answer text extracted from the context passage.
The CNN/DailyMail dataset is used for text summarization
task. The input comprises the article text to be summarized.
It is tokenized and encoded, with special tokens inserted to
indicate the beginning and end of the input. The output is the
human-generated summary corresponding to each article.
For the sentiment analysis, the input consists of text sentences extracted from the Financial Phrasebank dataset. Each
sentence is tokenized and encoded into integer sequences using
a tokenizer. Additionally, a special token is appended to denote
the sentiment label associated with the sentence. The output
corresponds to the sentiment label of each sentence. Sentiment labels are encoded as integers or strings, representing
categories such as positive, negative, or neutral sentiment. The
sentiment label is appended to the tokenized sequence as part
of the output.

# Results:
![image](https://github.com/Ema-Ans/LLM_from_scratch_gpt2_small/assets/87119440/bf301fc4-7bbd-4470-ba9e-5a40b492fcae)

# References:
[1] J. Devlin, M.-W. Chang, K. Lee, and K. Toutanova, “Bert: Pre-training
of deep bidirectional transformers for language understanding,” arXiv
preprint arXiv:1810.04805, 2018.
[2] A. Radford, K. Narasimhan, T. Salimans, I. Sutskever et al., “Improving
language understanding by generative pre-training,” 2018.
[3] A. Vaswani, N. Shazeer, N. Parmar et al., “Attention is all you need,”
arXiv preprint arXiv:1706.03762, 2017.
[4] T. B. Brown, B. Mann, N. Ryder et al., “Language models are few-shot
learners,” arXiv preprint arXiv:2005.14165, 2020.
[5] J. Howard and S. Ruder, “Universal language model fine-tuning for text
classification,” arXiv preprint arXiv:1801.06146, 2018.
[6] A. See, P. J. Liu, and C. D. Manning, “Get to the point: Summarization with pointer-generator networks,” arXiv preprint arXiv:1704.04368,
2017.
[7] Z. Lan, M. Chen, S. Goodman et al., “Albert: A lite bert for
self-supervised learning of language representations,” arXiv preprint
arXiv:1909.11942, 2019.
[8] C. Raffel, N. Shazeer, A. Roberts et al., “Exploring the limits of
transfer learning with a unified text-to-text transformer,” arXiv preprint
arXiv:1910.10683, 2019.
[9] K. Guu, K. Lee, Z. Tung, P. Pasupat, and M.-W. Chang, “Realm:
Retrieval-augmented language model pre-training,” arXiv preprint
arXiv:2002.08909, 2020.
[10] C. Sun, X. Qiu, Y. Xu, and X. Huang, “How to fine-tune bert for text
classification?” arXiv preprint arXiv:1905.05583, 2019.
[11] A. Conneau, K. Khandelwal, N. Goyal, V. Chaudhary, G. Wenzek,
F. Guzman, E. Grave, M. Ott, L. Zettlemoyer, and V. Stoyanov, “Unsu- ´
pervised cross-lingual representation learning at scale,” arXiv preprint
arXiv:1911.02116, 2020.
[12] G. Lample, M. Ballesteros, S. Subramanian, K. Kawakami, and C. Dyer,
“Neural architectures for named entity recognition,” arXiv preprint
arXiv:1603.01360, 2016.
[13] A. Akbik, D. Blythe, and R. Vollgraf, “Contextual string embeddings
for sequence labeling,” arXiv preprint arXiv:1808.03979, 2018.
[14] E. M. Bender, T. Gebru, A. McMillan-Major, and S. Shmitchell, “On
the dangers of stochastic parrots: Can language models be too big? ,”
Proceedings of the 2021 ACM Conference on Fairness, Accountability,
and Transparency, 2021
