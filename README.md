# 📚 Replication-Package-HFProject
**An Empirical Study on Hugging Face Trends, Topics, and Challenges on Stack Overflow**

## 📄 About

This repository contains the replication package for the paper **"An Empirical Study on Hugging Face Trends, Topics, and Challenges on Stack Overflow"**, accepted at the **2025 IEEE 49th Annual Computers, Software, and Applications Conference (COMPSAC)**.

📎 **Paper**: [IEEE Xplore](https://ieeexplore.ieee.org/document/11126738)

The study presents an empirical analysis of Stack Overflow discussions related to Hugging Face (HF) from 2019 to 2024. We investigate how HF-related discussions have evolved over time, identify the key topics discussed by developers, and assess which topics are the most popular and the most difficult. Using LDA topic modeling with multi-objective hyperparameter tuning, we uncover eight primary discussion topics and analyze their popularity and difficulty through metrics such as view counts, scores, and the percentage of unanswered questions.

## 📂 Repository Structure

- **📥 data_collection.ipynb**
 This notebook contains the data collection process.

 
- **📦 HF_SO_2019_2024.rar**   
 Contains the raw data collected from Stack Overflow posts related to Hugging Face. This dataset spans from 2019 to 2024 and includes metadata from relevan 
  questions and answers.
  

- **📊 RQ1_HF_Trends.ipynb**  
 This notebook addresses Research Question 1 (RQ1): "(Trends) How have the discussions about HF evolved on SO?"  
  - **Approach**: Analyzes the annual trends in user engagement, including the number of posts, the growth of tags, and user interactions over time.
  - **Findings**: a notable increase in discussion activity on HF starting from 2022, with contributions from over 5,838 unique users asking a total of 4,744 questions. Despite this rise, 75.7% of the questions remain without an accepted answer, indicating that many users still struggle to find adequate solutions. Our tag analysis, based on 890 distinct tags, shows that “Huggingface-Transformers” (22.6%) is the most frequently used tag, highlighting its prominent role in the HF ecosystem.


 ![distinct_users](https://github.com/user-attachments/assets/defaf03b-1b5a-44ee-9842-0aa359eaa02d)
 ![Nu_Q_W_WO_Answer_horizontal](https://github.com/user-attachments/assets/ca1a82ba-2635-4a81-b407-71d981f2c340)
 ![Growth_10 Popular_Tags](https://github.com/user-attachments/assets/5619e04f-09d3-4ee4-b6e3-196ea4a8adc5)

 - **📈 RQ2_TopicModeling.ipynb**
   This notebook addresses Research Question 2 (RQ2): "(Topics) What are the key topics discussed about HF?"  
   - **Approach**: Applies topic modeling using LDA and hyperparameters tuning using Optuna to identify key topics within the dataset.
   - **Findings**: Eight primary topics discussed by HF users on SO. These topics include: (1) Model Customization, (2) Model Training, (3) Model Deployment, (4) Environment, (5) Datasets, (6) Model Loading, Saving, and Pushing, (7) Distributed Computing and Resource Management, and (8) LLMs Usage and Understanding.
    
![topicDistribution](https://github.com/user-attachments/assets/9007f574-80f9-4f78-a170-7b6ca38efa7b)

- **📉 RQ3_difficulty_popularity.ipynb**
 This notebook addresses Research Question 3 (RQ3): "Which HF-related topics are most popular and difficult??"
   - **Approach**: Examines the the popularity anf difficulty topics using metrics (e.g., views, score, number of questions, number of questions withous answers, etc ).
   - **Findings**: “LLMs Usage and Understanding” is the most popular topic based both on the number of questions and the average score. However, “Environment” and “Model Loading, Saving, and Pushing” have higher average views but significantly fewer questions, indicating that these topics are likely easier to address. In contrast, “Distributed Computing and Resource Management” stands out as the most difficult topic.

![question_trends_per_topic](https://github.com/user-attachments/assets/4be48885-c244-4a0c-8545-646bbb770f26)
![image](https://github.com/user-attachments/assets/44535935-1ff0-4b58-b491-a7820df4c55f)









