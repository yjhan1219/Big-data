# Big-data
In this repository, I'll start a project to study the nature of policy documents, their temporal dynamics, their policy interactions, their roots in scientific evidence, and their coevolution with science. 
## Overview
Science is a public good, and it provides impacts beyond the community of scientists [1]. Yet, disconnects between scientists and policymakers, as illustrated by the “two communities” theory, where important scientific insights may be missed by policymakers, are a long-standing concern [2-3]. Despite society’s expectation for evidence-based policymaking, we lack a systematic understanding of policies worldwide and the science behind them.
## Datasets
We identified in total 11 million policy documents published worldwide in 2000-2022. For each policy document, we collected their metadata including title, author, year, source type, source country, language, classification, topic, and Sustainable Development Goals (SDG) category. We also provided the list of their policy references and science references. We further supplemented the data with the metadata of publications cited by policy documents.\
In this project, the data contains 6 CSV files in the “Data_5pct” folder (see below) and two folders. The main file is “df_policy_doc_info_2000_2022_5pct.csv”, which is a 5% of random sample policy documents (540K documents). There are two primary linkage files, including “df_policy_to_policy.csv”, and “df_policy_to_paper.csv”. The two subfolders provide detailed data about cited policy and cited paper, respectively. The other files should be self-explanatory by their names. More details about data and variables are in Ref [4] webpage and Ref [2-3].\
![image](https://github.com/user-attachments/assets/424e8918-e4ee-4298-8261-529b310f11c6)\
Considering that some participants may have difficulty processing large-scale datasets due to laptop limitations, we also provided a 1% of random sample policy documents (110K documents; see the “Data_1pct” folder), where the data files follow the same structure.
## Tasks
These datasets allow us to study the nature of policy documents, their temporal dynamics, their policy interactions, their roots in scientific evidence, and their coevolution with science. In the following, we list some specific computational tasks and open questions to explore:\
T1. Plot time trends in global policy priorities cross three categories including science & health, economy & labor, and society (see “Classification_Category.xlsx”).\
T2. Identify the top five SDGs that policy documents focus on the most and explore further what are the most discussed topics in policies for each of these SDGs.\
T3. What are the most highly cited policy docs by other policy docs published in 2010, 2015, and 2022? What about “Mental health” and “Poverty” (topic) policies?\
T4. What are the most highly cited research publications by policy docs? What are their research disciplines? Which countries and institutions published the research?\
T5. Is public policy making becoming increasingly evidence-based? Which countries (research areas) see more reliance and which countries (areas) have greater deviations?\
## References
[1] Yin, Y., Dong, Y., Wang, K., Wang, D., & Jones, B. F. (2022). Public use and public funding of science. Nature Human Behaviour, 6(10), 1344-1350.\
[2] Gao, J., Yin, Y., Jones, B. F., & Wang, D. (2020). Quantifying policy responses to a global emergency: Insights from the COVID-19 pandemic. arXiv:2006.13853.\
[3] Yin, Y., Gao, J., Jones, B. F., & Wang, D. (2021). Coevolution of policy and science during the pandemic. Science, 371(6525), 128-130.\
[4] Documentation for Overton database. https://app.overton.io/swagger.php.\
## Link to Data:
https://www.dropbox.com/scl/fo/zbii0mfw8brec3gmtvwhi/AMZJ08HtlGJVcjUhM5UfmLQ?rlkey=uyauiu5u71mtnbaqgqgcovmco&dl=0
