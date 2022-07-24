# Data Preparation Stage

- Convert my data into train and test.tsv in 70:30 ratio

'''
data.xml
    |-train.tsv
    |-test.tsv
'''
- We are choosin only three tags in xml data - 1. row Id, 2. title and body, 3. tags (Stackoveflow tags specific to python)

|Tags|Features names|
|-|-|
|row Id|row Id|
|title and body|text|
|stackoverflow tags|Label - Python|