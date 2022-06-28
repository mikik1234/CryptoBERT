# CryptoBERT
CryptoBERT - this model was trained to best grasp the language of cryptocurrency investors. Since they primarily communicate in informal, social media settings, the model was trained precisely on those. 

We used over 3.2 million unique crypto-related posts from StockTwits, Telegram, Twitter and Reddit to pretrain this model, building upon cardiffnlp's Twitter Roberta Base. 

The model was further fine-tuned for the investor's sentiment classification task, on over 2M posts, to predict whether a given post is 'Bullish', 'Bearish' or 'Neutral'. 

CryptoBERT yields state-of-the-art sentiment predictions on our test set of 83257 new, unique StockTwits posts.


For more information on the model, or to right-way retrieve it, please follow the link below to its repo on HuggingFace:

https://huggingface.co/ElKulako/cryptobert


Paper, article and github submission will follow soon!!!
