# Predicting Subjective Features from Questions on QA Websites using BERT

Implementation for the paper "Predicting Subjective Features from Questions on QA Websites using BERT", which has been accepted by ICWR'2020. https://arxiv.org/abs/2002.10107

## Abstract

Modern Question-Answering websites, such as StackOverflow and Quora, have specific user rules to maintain their content quality. These systems rely on user reports for accessing new content, which has serious problems including the slow handling of violations, the loss of normal and experienced users' time, the low quality of some reports, and discouraging feedback to new users. Therefore, with the overall goal of providing solutions for automating moderation actions in Q&A websites, we aim to provide a model to **predict 20 quality or subjective aspects** of questions in QA websites. To this end, we used **data gathered by the CrowdSource team at Google Research in 2019** and a fine-tuned pre-trained BERT model on our problem.
Based on the evaluation by Mean-Squared-Error (MSE), the model achieved a value of 0.046 after 2 epochs of training, which did not improve substantially in the next ones. Results confirm that by simple fine-tuning, we can achieve accurate models in little time, and on less amount of data.

Full article: https://arxiv.org/abs/2002.10107


## Related data

https://www.kaggle.com/datasets/akensert/sacremoses

https://www.kaggle.com/datasets/akensert/bert-base-uncased-huggingface-transformer

https://www.kaggle.com/competitions/google-quest-challenge
