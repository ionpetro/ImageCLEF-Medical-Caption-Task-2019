# ImageCLEF-Medical-Caption-Task-2019

## Assignment

Find the assignment [here](assignment/imageclef.ipynb)

## Get the Data

You can download the training and validation data from <https://drive.google.com/uc?id=1UOccw0VNCiRTwaQSEJMhiYWXhizvKptX> and the test data from <https://drive.google.com/uc?id=1diO2apPPFJeTH8CGcd3S55OUNTXtJVu2>. Alternatively, you can use the [gdown](https://github.com/wkentaro/gdown) utility; the file IDs are `1UOccw0VNCiRTwaQSEJMhiYWXhizvKptX` and `1diO2apPPFJeTH8CGcd3S55OUNTXtJVu2`.

## Models trained

1. CNN v1
2. CNN v2
3. Transfer Learning with ```mobilenet``` of Google
3. CNN v3

## Evaluation

To evaluate the model find the script [here](evaluation/evaluate-f1.py)

Use this syntax:

```python evaluate-f1.py path/to/candidate/file path/to/ground_truth/file```

## My test results

You can find it [here](test_results/candidate_test_file.tsv)

## Libraries used for the assignment

* keras
* tensorflow
* os
* pandas
* matplotlib
* numpy
* cv2
