# university_nirs
### This repository presents a scientific research paper, the purpose of which was the automatic detection of unwanted messages in the topic of cryptocurrencies. This topic is very relevant, since currently we often have to deal with spam in this topic, especially for those for whom this area is professional.

### The Russian language was used for the work, however, you can always adapt the results to the language you need (ask questions if it is not clear how).

### The source dataset consists of 50 texts from the spam category and 50 texts from the non-spam category.

### The research process is described in the following notebooks:
* `form_data_and_analysis.ipynb` - getting data from text files, preprocessing text, getting embeddings;
* `siamese_network_via_key_words.ipynb` - solving the problem by feeding the Siamese neural network the obtained vectors of five keywords for each text;
* `siamese_model_via_sentense_vectors.ipynb` - similar to the point above, only one embedding for each text is served to the Siamese network;
* The `extract_rus_key_words_inbox.ipynb` and `extract_rus_key_words.ipynb` auxiliary files demonstrate universal procedures for extracting keywords or phrases from text.

## The result of the study was that for the Siamese model, the best indicator (0.77 f1 test score) was given by the case when only one embedding (notebook) was used from the text.

### I am open to further steps, if you have any ideas on how to improve the result, do not hesitate to contact.
