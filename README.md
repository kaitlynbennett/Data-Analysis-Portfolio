# Data-Analysis-Portfolio
## About
Hi, I'm Kaitlyn! I have completed my BS degree with a major in Business Management and a minor in Management Information Systems, which has allowed me to acquire a strong foundation in business principles, management skills, strategic thinking, and technology integration. By combining my skills in data analysis with my passion for promoting diversity and inclusion, I strive to make a tangible difference in the representation of women in technology. 

During my studies, I honed the ability to work with complex data and developed a keen eye for identifying patterns and trends. A degree in business management has provided me with a solid understanding of various functional areas within an organization, such as marketing, finance, operations, and human resources. This knowledge allows me to contextualize data within the business environment, identify relevant metrics, and generate insights that align with the organizational goals. My minor has equipped me with a diverse set of technical skills, including proficiency in tools such as; Excel, Access, SQL, Tableau, Gephi and RapidMiner.

In this portfolio, I have included a variety of projects that showcase my data analytics skills, demonstrating my ability to tackle complex business challenges and deliver actionable insights. I have also included examples of my work in data mining and statistics. These projects showcase my ability to extract meaningful insights from large datasets, and combining data from multiple sources to create a comprehensive view of the data.

This repository is to showcase my skills, share projects and track progress in Data Analytics related topics.

## Table of Contents
**About**

**Bank Churning Factors**

**Restaurant Database**

**Sentiment Analysis on Movie Reviews**

**Contact**

## Bank Churning Factors
**Goal:** To provide actionable insights and recommendations to mitigate customer churn.

**Description:** The project focused on identifying and visualizing key factors contributing to bank churners. To begin the project, I collected and analyzed a comprehensive dataset that contained various customer attributes and churn information. The dataset encompassed factors such as demographics, account types, and customer churn status.

Firstly, I developed interactive dashboards that showcased key metrics and trends related to customer churn. These dashboards enabled me to analyze the overall churn rate, identify churn patterns over time, and gain a comprehensive view of the customer churn landscape.

Next, I employed various visualizations, such as bar charts, pie charts, and heat maps, to explore the relationship between customer attributes and churn. By visualizing customer demographics, account types, transaction patterns, and customer interactions, I sought to identify any significant correlations or patterns that could shed light on the factors influencing churn.

Additionally, I utilized Tableau's advanced features, including filters, parameters, and drill-down capabilities, to delve deeper into the data. This allowed me to conduct detailed exploratory analysis and investigate potential factors at a granular level.

**Skills:** data cleaning, data analysis, data visualization, dashboard creation, data mining, statistical analysis.

**Technology:** Tableau

**Results:** The most prominent time to churn is at 36 months. The credit card category indicates those with no annual fees are more likely to have bank chruners sign on then cancel after getting the rewards.
The result of this project was a comprehensive understanding of the factors contributing to bank churners, gained through data analysis and visualization. They key outcomes and results achieved include:
1. Identification of Key Churn Factors: Through the analysis and visualiztion of customer data, I successfully identified the signififcant factors that contribute to bank churn. These factors include account types and customer interactions. The factor of credit card type indicates those with no annual fees are more likely to have churners sign on then cancel after getting the rewards.

2. Actionable Insights and Recommendations: The project resulted in actionable insights and recommendations to mitigate customer churn. By analyzing the identified churn factors, I provided valuable information for the bank to develop targeted strategies and interventions. These recommendations may include personalized customer retention campaigns, improved customer support initiatives, or product enhancements based on the identified factors.

3. Enhanced Customer Retention Strategies: Armed with the knowledge of influential churn factors, the bank can develop and refine their customer retention strategies. By focusing on the identified factors, they can prioritize efforts and resources on retaining customers who are most at risk of churning, resulting in improved customer satisfaction and long-term loyalty.

## Restaurant Database
**Goal:** To design and implement a functional database system for a restaurant to ensure .

**Description:** The database I developed encompassed various entities and relationships, enabling seamless management of restaurant operations. The core entities included customers, employees, suppliers, orders, and recipes. 

For customers, I designed a schema that encompassed essential information such as names, contact details, and preferences. This allowed for personalized service and streamlined communication with customers.

In regards to employees, I developed a system that stored employee profiles, including their roles, contact information, and work schedules. The database also incorporated delivery drivers, allowing the restaurant to efficiently manage deliveries. This enabled the restaurant management to better assign tasks and manage shifts.

Suppliers played a vital role in the restaurant's supply chain, and I incorporated their information into the database. This allowed the restaurant to maintain a record of suppliers, their contact details, and the ingredients they provided.

The ordering system was an integral part of the database, allowing the restaurant to process and track orders. By implementing order history functionality, the database kept a comprehensive record of past orders, facilitating analysis and tracking customer preferences.

The inclusion of menu items and ingredients allowed the restaurant to manage its menu effectively. The database stored information about recipes and the quantity of each ingredient used, while menu items detailed the names and prices. This streamlined menu management and enhanced the overall functionality of the restaurant's menu offerings.

Lastly, to address allergy concerns, I integrated allergy information into the database. This allowed the restaurant staff to quickly identify allergens present in each dish, providing valuable information for customers and ensuring their safety.

**Skills:** database design, data modeling, data management, data analysis, ER diagram, normalization techniques

**Technology:** SQL

**Results:** The result of this project was the successful implementation of a robust and efficient database system for the restaurant. They key outcomes and benefits achieved include:
1. Improved Data Management: Databse provided a centralized and well-structured platform for storing and managing various entities. This ensured easier access, retrieval, and manipulation of data, enhancing overall data management efficiency.
   
2. Streamlined Operations: The implemented database system streamlined various restaurant operations, including order processing, inventory management, customer management, and menu planning. This reduced manual efforts and increased operational efficiency.
   
3. Accurate Inventory Tracking: With the inclusion of ingredients and recipes, the database facilitated precise inventory tracking. This ensured better control over ingredient quantities, reduced waste, and improved inventory management.
   
4. Scalability and Future Growth:The database considered scalability, allowing for easy expansion and adaptation as the restaurant grows. It provided a foundation for future enhancements and integration with additional systems or technologies.
  
5. Data Analysis and Insights: The system enabled the extraction of valuable insights through data analysis. This included identifying popular dishes, tracking customer preferences, analyzing sales patterns, and generating reports. These insights supported informed decision-making and helped optimize business strategies.

## Sentiment Analysis on Movie Reviews
**Goal:** Develop a predictive model that could estimate the rating customers would likely assign to a movie they hadn't watched.

**Description:** To begin the project, I collected a dataset about movies, such as genre, cast, director, plot summary, and other relevant attributes. Additionally, I gathered customer reviews and ratings for a set of movies to serve as labeled data for model training and evaluation.

I utilized data preparation tools to clean and transform the movie and review data into a suitable format for analysis. This included handling missing values, encoding categorical variables, and normalizing numerical attributes.

I employed feature selection techniques to identify the most relevant attributes that could contribute to predicting customer sentiment. This involved analyzing the correlation between attributes and the target variable, applying statistical tests, or using machine learning algorithms for feature importance ranking.

I trained machine learning algorithms available in RapinMiner, such as support vector machines, on the labeled movie review data. I split the dataset into training and testing sets to evaluate the models' performance and select the best-performing algorithm.

Using the trained model, I made predictions on the unseen movies by feeding their attributes as input. RapidMiner allowed me to generate predicted ratings for these movies, which I then evaluated against actual customer reviews to assess the model's predictive performance.

**Skills:** data preprocessing, feature selection, machine learning, model training and evaluation, predictive analytics

**Technology:** RapidMiner

**Results:** The result of this project was the successful development of a predictive model using RapidMiner to estimate customer reviews for unseen movies. The key outcomes and results achieved include:
1. Predictive Model: Creation of a robust and accurate predictive model capable of estimating customer sentiment for movies that customers had not watched yet. The model was trained using machine learning algorithms and evaluated using appropriate metrics to ensure its reliability and performance.

2. Decision Support: Provided decision support for movie studios, streaming platforms, and marketers. The predictive model enabled stakeholders to make informed decisions regarding movie releases, marketing campaigns, or investment decisions based on anticipated customer sentiment and ratings.

3. Improved Decision-Making: Contributed to enhanced decision-making processes within the movie industry. By incorporating data-driven insights into the decision-making process, stakeholders were empowered to align their strategies with customer preferences and market trends, leading to more informed and effective decisions.

4. Competitive Advantage: The project's outcome provides a competitive advantage for movie studios or streaming platforms. Anticipating customer sentiment and ratings for unseen movies allows stakeholders to differentiate themselves by offering content tailored to customer preferences, resulting in increased customer engagement and loyalty.
