# icassp 22
1. Unzip the zip file.
2. Concatenate the alics_data_* to one file.
3. preprocess_al.py: preprocess alibaba dataset
4. calw2c_tfidf, calw2s_tfidf: calculate the tfidf for sentences and conversation.
5. data_loader.py: load preprocessed data to construct heterogeneous graph.
6. train.py: train and evaluate model.
7. predict.py: predict label with trained model.
8. utils/config.py: configuration.
9. utils/log.py: record the log.
10. models/HiGraph.py: The heterogeneous graph model.
