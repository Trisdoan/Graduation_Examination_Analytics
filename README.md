# Graduation_Examination_Analytics

Credit: Dung Lai

You can view his course here: https://dunglailaptrinh.com/L-p-H-c-Data-Science-C-B-n-Python-c735d90b891a4351b658fff8d8cab589

# Insights
1. dfds
2. ádasd
3. dsasd



# What I did in this dataset:
1. Used FileIO to read data.txt
2. Used basic techniques to extract clean data
3. Visualized the following insights:
    * Top first names of candidates
    * Top last names of candidates
    * Avarage scores of 11 groups of ages
    * Average scores of candidates who did not sit for some subjects
    * Numbers of candidates who did not sit for some subjects

<img src="images/1.jpg" width="300"/> <img src="images/1.jpg" width="300"/> <img src="images/1.jpg" width="300"/>

# Explained approach

## Import dataset

```python
import csv
file = open("raw_data.txt", "r")
datas = file.read().split("\n")
```
## Add header to file

```python
with open("clean_data.csv", "w", encoding="utf8", newline ="") as file_csv:
	header = ["sbd", "tên", "dd", "mm", "yy", "toán", "ngữ văn", "khxh", "khtn", "lịch sử", "địa lí", "gdcd", "sinh học", "vật lí", "hóa học", "tiếng anh"]
	writer = csv.writer(file_csv)
	writer.writerow(header)
 ```
