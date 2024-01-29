# Introduction
In this case study, I worked for a fictional company. In order to answer the business questions, follow the steps of the data analysis process: Ask, Prepare, Process, Analyze, Share, and Act. 



# Ask
### Guiding Questions:
#### • What is the problem you are trying to solve?
Bellabeat seeks insights into how users of smart devices utilize their devices to monitor and enhance their health and well-being. This understanding is crucial for identifying potential areas of growth and innovation for the company.

#### • How can your insights drive business decisions?

Will analyze how users are utilizing the Leaf smart device. This will involve finding relevant patterns and trends in whatever information can be found in the dataset.

### Deliverable
#### • A clear statement of the business task

Will propose recommendations for Bellabeat’s marketing strategy.




# Prepare
### Guiding questions
#### • Where is your data located?

The data is stored on Kaggle as a dataset named [FitBit Fitness Tracker Data](https://www.kaggle.com/datasets/arashnic/fitbit).

#### • How is the data organized?

The data consists of 18 csv files. Used only three of them namely dailyActivity_merged.csv, sleepDay_merged.csv, weightLogInfo_merged.csv .

#### • How did you verify the data’s integrity?

The dataset was thoroughly reviewed, ensuring uniformity in column structure, including both the quantity and names, and maintaining consistency in data types across the entire dataset.

#### • How does it help you answer your question?

One valuable feature of smart wearable devices is their ability to motivate users to adopt healthier lifestyles. A potential enhancement could involve implementing a peer comparison feature. This feature aims to encourage users to elevate their activity levels by providing comparisons with peers, fostering a sense of friendly competition and motivation to improve overall health

### Deliverable
#### * A description of all data sources used

Out of the 18 available CSV files, I utilized only three: dailyActivity_merged.csv, sleepDay_merged.csv, and weightLogInfo_merged.csv for the analysis.





# Process
The individual CSV files were consolidated into one to facilitate easier manipulation and analysis. The combined file underwent a cleaning process, and supplementary columns were added for further insights.

### Guiding questions
#### • What tools are you choosing and why?
I opted for Python and Jupyter Notebook due to the dataset's size, which is too large for spreadsheets. The use of Python enables in-depth analysis and manipulation capabilities.

#### • What steps have you taken to ensure that your data is clean?
I performed data cleaning, which involved removing NA values and duplicates. Additionally, I formatted the time and dates in the datasets inorder to merge the content and dropped few columns.

#### • How can you verify that your data is clean and ready to analyze?
The steps taken for cleaning process can be reffered in the attached [notebook](https://github.com/ajoyscorpion/fitness_tracker_caseStudy_2/blob/main/fitness.ipynb).

#### • Have you documented your cleaning process so you can review and share those results?
The document has been cleaned

### Deliverable
Documentation of any cleaning or manipulation of data can be reffered in the attached [notebook](https://github.com/ajoyscorpion/fitness_tracker_caseStudy_2/blob/main/fitness.ipynb)


# Share
### Guiding questions

● What story does your data tell?

The analysis reveals a direct correlation between the distance traveled and the calories burned. As the distance increases, there is a corresponding increase in the calories burnt. Interestingly, individuals who sleep less than 6 hours per day and those who sleep more than 8 hours per day tend to burn fewer calories compared to individuals with a sleep duration between 6 and 8 hours. This suggests that the duration of sleep may play a role in the relationship between sleep and calorie expenditure, with optimal results observed in the 6-8 hours sleep range for similar distances covered.

● How do your findings relate to your original question?

The analysis indicates a clear relationship between sleep duration and calories burned. It suggests that monitoring and optimizing sleep can be beneficial for weight loss goals. Individuals who achieve an optimal sleep duration may experience better outcomes in terms of calories burned, emphasizing the importance of quality sleep in overall health and wellness. This information can be effectively communicated to customers, highlighting the positive impact of adequate sleep on their weight loss journey and encouraging them to prioritize and track their sleep patterns for better health outcomes.

● Can data visualization help you share your findings?

Using data visualization provides a clear and concise way to analyse the realtionship between sleep, daily activity and calories burned

### Deliverable
Visualization are attached in the [notebook](https://github.com/ajoyscorpion/fitness_tracker_caseStudy_2/blob/main/fitness.ipynb).

# Act

The analysis highlights a compelling connection between sleep and calories burned, presenting an opportunity for Bellabeat to promote the significance of adequate sleep in achieving weight loss goals. Implementing a targeted marketing strategy focusing on educating users about the importance of sufficient sleep, how to attain it, and showcasing Bellabeat's tracking capabilities can enhance user engagement. Additionally, integrating a peer comparison feature can further motivate customers to elevate their activity levels, fostering healthier lifestyles and contributing to their overall well-being.


