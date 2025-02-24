# NYC School Regents Exam Analysis

## Introduction
The New York State (NYS) Regents exams are assessments that test public school students' understanding of high school learning standards in English, math, science, social studies, and foreign languages. The exams are administered three times ever year: January, June, and August. Students generally must pass a certain number of Regents exams to graduate with a traditional high school diploma. Some middle schools in the state offer accelerated programs that teach the standards and enable students to earn high school credit before matriculation into high school.

In this analysis, I explore the performances of New York City (NYC) public schools on the Regents exams. The analysis starts with an overview of the performance of NYC schools, then it delves more into the differences in performance by English Language Learner (ELL) status and Students with Disability (SWD) status. The time period covered in this analysis is from 2017 to 2023 (excluding 2020 and 2021 due to COVID's impact on the exam administration). The goal is to identify interesting insights into the academic performance of students in the NYC public school system.

The analysis is written up in a Jupyter notebook with interactive visuals. The visuals are not rendered on GitHub. See below for instructions on how to see the visuals on Google Colab.

Here are examples of the visuals:

This plot shows the distribution of Mean Scores on the Common Core English exam from 2017 to 2019. See notebook for details.

![Example 1](https://github.com/user-attachments/assets/7c19b3df-5daa-4297-83eb-8c8e11dc5377)

This plot shows the distribution of Mean Scores from students with disabilities and students without disabilities on the Common Core English exam from 2017 to 2023 (excluding 2020 and 2021). See notebook for details.

![Example 2](https://github.com/user-attachments/assets/8046b78c-6341-4f1b-a11c-6854d7eda59d)

## How to Visualize the Data on Google Colab:

You can run the notebook on Google Colab to see the interactive visuals. You need to upload the notebook to Google Colab. You also need the following three files to run the entire notebook. The first file is the data source, while the remaining two files help correct the names of misspelled schools.

*   2015_to_2023_regents_data.xlsx
*   new_names.txt
*   original_names.txt

Data Source:

2015 to 2023 Regents Exam Results. NYC Public Schools InfoHub. Last accessed in January 2025. https://infohub.nyced.org/reports/academics/test-results

*Disclaimer: Any opinion in this analysis is my own and does not represent the opinion of the NYC education department or my current and previous employers.*
