# GooglePlayStoreApps-Data-Analysis
This project, titled Google Play Store Apps (Regulatory Affairs), focuses on performing an in-depth exploratory data analysis of applications available on the Google Play Store. The primary objective is to analyze app-related features such as category, rating, reviews, size, installs, price, content rating, genres, and Android version requirements to identify patterns, trends, and business insights.

The dataset contains more than 10,000 apps with 13 different attributes. Using tools like Python, Machine Learning, SQL, and Excel, the project begins with importing essential libraries such as Pandas, NumPy, Matplotlib, and Seaborn for data manipulation and visualization. The dataset is loaded into a dataframe and explored using functions like head(), info(), and describe() to understand its structure and statistical properties.

Data cleaning is a crucial step in this project. Missing values in columns like Rating and Size are handled, incorrect records are removed, and columns such as Reviews, Installs, and Price are converted into appropriate numeric formats. Special characters like ‘+’, ‘$’, and commas are removed to ensure accurate computation. The Size column is converted into bytes for better analysis.

After preprocessing, visualizations such as histograms, bar charts, and scatter plots are created to study rating distribution, category popularity, and the relationship between installs and ratings. Additional analysis includes identifying top-installed apps, average ratings by category, and install-based segmentation.

Overall, this project helps understand market behavior, user preferences, and business opportunities in the Android app ecosystem.
