# U-Vectors: Generating Clusterable Speaker Embedding from Unlabeled Data

##### By  Muhammad Firoz Mridha, Abu Quwsar Ohi, Muhammad Mostafa Monowar, Md. Abdul Hamid, Md. Rashedul Islam, and Yutaka Watanobe

###### This is the official implementation of U-vector, by Abu Quwsar Ohi.

###### Original paper is published in Applied Sciences: [Link](https://doi.org/10.3390/app112110079)

**Abstract:** Speaker recognition deals with recognizing speakers by their speech. Most speaker recognition systems are built upon two stages, the first stage extracts low dimensional correlation embeddings from speech, and the second performs the classification task. The robustness of a speaker recognition system mainly depends on the extraction process of speech embeddings, which are primarily pre-trained on a large-scale dataset. As the embedding systems are pre-trained, the performance of speaker recognition models greatly depends on domain adaptation policy, which may reduce if trained using inadequate data. This paper introduces a speaker recognition strategy dealing with unlabeled data, which generates clusterable embedding vectors from small fixed-size speech frames. The unsupervised training strategy involves an assumption that a small speech segment should include a single speaker. Depending on such a belief, a pairwise constraint is constructed with noise augmentation policies, used to train AutoEmbedder architecture that generates speaker embeddings. Without relying on domain adaption policy, the process unsupervisely produces clusterable speaker embeddings, termed unsupervised vectors (u-vectors). The evaluation is concluded in two popular speaker recognition datasets for English language, TIMIT, and LibriSpeech. Also, a Bengali dataset is included to illustrate the diversity of the domain shifts for speaker recognition systems. Finally, we conclude that the proposed approach achieves satisfactory performance using pairwise architectures. 

The paper is a direct improvement of [AutoEmbedder](https://github.com/QuwsarOhi/AutoEmbedder) architecture, which was proposed for semi-supervised learning.

There are two programs (currently unmodified, but I would surely modify it when I get enough time), one for data preparation and the other for training.


## Cite this code

    @misc{uvectors_script2021,
      author =       {Abu Quwsar Ohi},
      title =        {{U-Vectors: Generating Clusterable Speaker Embedding from Unlabeled Data (script)}},
      howpublished = {\url{https://github.com/QuwsarOhi/u-vectors}},
      year =         {2021}
    }

## Cite the paper

    @article{app112110079,
      author = {Mridha, Muhammad Firoz and Ohi, Abu Quwsar and Monowar, Muhammad Mostafa and Hamid, Md. Abdul and Islam, Md. Rashedul and Watanobe, Yutaka},
      title = {U-Vectors: Generating Clusterable Speaker Embedding from Unlabeled Data},
      journal = {Applied Sciences},
      volume = {11},
      year = {2021},
      number = {21},
      article-number = {10079},
      url = {https://www.mdpi.com/2076-3417/11/21/10079},
      issn = {2076-3417},
      doi = {10.3390/app112110079}
    }
    
