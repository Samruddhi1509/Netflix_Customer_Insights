# Netflix Customer Insights Analysis
This project digs into customer behavior data to uncover trends that can help shape business strategy. The main goal was to explore how customers interact with the platform, what drives their engagement, and where opportunities exist to improve retention.

Business problem: Improving retention and engagement across subscription tiers

Data Cleaning & Preparation
- Tools: Python( Pandas, Numpy, Scikit-learn, Seaborn, Matplot)
- Loaded a dataset of Netflix users with attributes such as Age, Country, Subscription Type, Watch Time, Last Login, and Genre.
- Created new variables to enhance analysis:
    Age bins to group users into meaningful cohorts
    Recency metric from Last_Login → days since last login
    Heavy_Watcher flag → top 25% of users by watch time


*Key Insights & Recommendations*
Our analysis revealed that Romance and Drama dominate overall watch time, while Comedy is emerging as a promising growth lever for specific audience groups. To capitalize on this, the platform should invest in expanding Comedy and Documentary content, as they perform close to the top genres and could drive overall watch time higher.
<img width="641" height="442" alt="Screenshot 2025-09-22 at 4 36 09 PM" src="https://github.com/user-attachments/assets/9c6d1aa7-2a5f-47e6-9816-5ca16d50d092" />


We also found that a significant share of users have not logged in for 15+ days, indicating potential churn risk. This segment represents a clear opportunity for reactivation. Personalized re-engagement campaigns—such as tailored emails, push notifications, or targeted ads that highlight trending shows in users’ preferred genres—can help bring these customers back.
<img width="437" height="283" alt="Screenshot 2025-09-22 at 4 36 38 PM" src="https://github.com/user-attachments/assets/4998c185-06e3-4c62-b077-6928e1eaeac6" />

In terms of demographics, senior citizens (65+) make up the largest share of the audience, while user numbers remain steady across the 25–54 group. However, teen users (<17) are the least active on the platform. Introducing more youth-oriented content, such as trending series, gamified features, or exclusive releases for this demographic, could strengthen retention and broaden the platform’s customer base.
<img width="473" height="351" alt="Screenshot 2025-09-22 at 4 35 39 PM" src="https://github.com/user-attachments/assets/b9ac1db5-5d54-4115-a807-db445e491edd" />

