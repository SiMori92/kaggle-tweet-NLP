# Problem Defination:
This challenge is to determine whether a tweet is a disaster tweet or not, making it a classification problem.

## Index:
1. Basic library loading
2. Import data
3. Basic statistics
- The size of Training & Test dataset
- check missing data
- Cardinality analysis ((for other 2 features - keywords & location))
- check the number of duplicated values of text with multiple target
- imbalance class checking & downsample
- Meta Features (understand the structure between training & test dataset) (文本的統計特徵)
- Target and N-grams (理解一個文本中詞彙序列的使用情況和組合方式)
5. Data processing
- clean the text
- handle Mislabeled Samples
- handle missing value
- Cross-validation of unique keyword
6. Model
7. Evaluation
