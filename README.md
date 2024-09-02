## Student Performance Indicator.
This model understand and predict how well the student perform in terms of test score under various factor like gender , Parent level of education etc.

Dataset Source - https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977
The data consists of 8 column and 1000 rows.

plt.subplots(1,3, figsize=(20,6))

plt.subplot(131)
plt.title('Maths Score')
sns.violinplot(data=data, y='math_score', color='red')

plt.subplot(132)
plt.title('Reading Score')
sns.violinplot(data=data, y='reading_score', color='yellow')

plt.subplot(133)
plt.title('Writing Score')
sns.violinplot(data=data, y='writing_score', color='green')
