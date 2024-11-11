# 📚 Replication-Package-HFProject
**An Empirical Study on Hugging Face Trends, Topics, and Challenges on Stack Overflow**

## 📂 Repository Structure

- **📦 HF_SO_2019_2024.rar**   
  Contains the raw data collected from Stack Overflow posts related to Hugging Face. This dataset spans from 2019 to 2024 and includes metadata from relevan 
  questions and answers.

- **📊 RQ1_HF_Trends.ipynb**  
 This notebook addresses Research Question 1 (RQ1): "(Trends) How have the discussions about HF evolved on SO?"  
  - **Objective**: Analyzes the annual trends in user engagement, including the number of posts, the growth of tags, and user interactions over time.
  - **Findings**: a notable increase in discussion activity on HF starting from 2022, with contributions from over 5,838 unique users asking a total of 4,744 questions. Despite this rise, 75.7% of the questions remain without an accepted answer, indicating that many users still struggle to find adequate solutions. Our tag analysis, based on 890 distinct tags, shows that “Huggingface-Transformers” (22.6%) is the most frequently used tag, highlighting its prominent role in  
  the HF ecosystem.


 ![distinct_users](https://github.com/user-attachments/assets/defaf03b-1b5a-44ee-9842-0aa359eaa02d)
 ![Nu_Q_W_WO_Answer_horizontal](https://github.com/user-attachments/assets/ca1a82ba-2635-4a81-b407-71d981f2c340)
 ![Growth_10 Popular_Tags](https://github.com/user-attachments/assets/5619e04f-09d3-4ee4-b6e3-196ea4a8adc5)

 - **📈 RQ2_TopicModeling.ipynb**
   This notebook addresses Research Question 2 (RQ2): "(Topics) What are the key topics discussed about HF?"  
  - **Purpose**: Applies topic modeling using LDA and hyperparameters tuning using Optuna to identify key topics within the dataset.
  - **Findings**: Eight primary topics discussed by HF users on SO. These topics include: (1) Model Customization, (2) Model Training, (3) Model Deployment, (4) Environment, (5) Datasets, (6) Model Loading, Saving, and Pushing, (7) Distributed Computing and Resource Management, and (8) LLMs Usage and Understanding.
    
![topicDistribution](https://github.com/user-attachments/assets/9007f574-80f9-4f78-a170-7b6ca38efa7b)



