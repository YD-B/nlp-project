# Datasets

## **setfit-absa-semeval-restaurants-ru**

Russian translation of a snippet from the dataset *[setfit-absa-semeval-restaurants](https://huggingface.co/datasets/tomaarsen/setfit-absa-semeval-restaurants)* (843/3692) (manually annotated restaurant reviews from SemEval-2014 Task 4, in the format as understood by SetFit ABSA). Translated with the help of Yandex Translate and DeepSeek.

**Data Fields**
- *text*: a string feature.
- *span*: a string feature showing the aspect span from the text.
- *label*: a string feature showing the polarity of the aspect span.
- *ordinal*: an int64 feature showing the n-th occurrence of the span in the text. This is useful for if the span occurs within the same text multiple times.

## **setfit-absa-semeval-restaurants-ru-bal**

First 100 rows of each label value in *setfit-absa-semeval-restaurants-ru* (391/843).

## **setfit-absa-semeval-laptops-ru-bal**

First 100 rows of each label value in *[setfit-absa-semeval-laptops](https://huggingface.co/datasets/tomaarsen/setfit-absa-semeval-laptops)* (345/2358) translated to russian with the DeepSeek.

## **506.Synthetic_train-bal**

First 200 rows of each label value in the training dataset from *[506.Synthetic](https://github.com/yangheng95/ABSADatasets/tree/v2.0/datasets/acos_datasets/506.Synthetic)* (544/2356) modified to the format understood by SetFit ABSA.

## **setfit-absa-semeval-ru3**

This dataset is a merge of datasets *setfit-absa-semeval-restaurants-ru* and *setfit-absa-semeval-laptops-ru-bal* without the label 'conflict'.

**Data Fields**
- *text*: a string feature.
- *span*: a string feature showing the aspect span from the text.
- *label*: a string feature showing the polarity of the aspect span.
- *ordinal*: an int64 feature showing the n-th occurrence of the span in the text. This is useful for if the span occurs within the same text multiple times.
- *norm_span*: a string feature showing the normalized aspect span from the text.