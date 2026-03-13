# denver-airbnb-exploratory-data-analysis
Exploratory data analysis of Airbnb listings in Denver, including pricing, reviews, and neighborhood trends.
# Denver Airbnb Exploratory Data Analysis

## 📌 Project Overview
This project explores Airbnb listing data in Denver, Colorado to identify pricing trends, customer behavior patterns, and neighborhood-level insights.

The goal was to conduct an open-ended exploratory data analysis (EDA) to uncover meaningful relationships within the dataset and generate data-driven questions for further investigation.

---

## 🎯 Business Questions
- How are nightly prices distributed?
- Is there a relationship between price and number of reviews?
- Do minimum night requirements impact booking frequency?
- Are there pricing differences across neighborhoods?
- How might pricing patterns relate to neighborhood-level equity indicators?

---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy)
- Matplotlib
- Seaborn
- Scikit-learn (StandardScaler, KMeans, silhouette_score)
- GeoJSON (spatial mapping)
- Jupyter Notebook

## Interactive Dashboard
View the interactive dashboard on Tableau Public:

🔗 https://public.tableau.com/views/DenverAirbnbMarketAnalysisFinal/AIRBNBDENVERANALYSIS

<div class='tableauPlaceholder' id='viz1773420645746' style='position: relative'><noscript><a href='#'><img alt='Denver Airbnb Market Analysis ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;De&#47;DenverAirbnbMarketAnalysisFinal&#47;AIRBNBDENVERANALYSIS&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='DenverAirbnbMarketAnalysisFinal&#47;AIRBNBDENVERANALYSIS' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;De&#47;DenverAirbnbMarketAnalysisFinal&#47;AIRBNBDENVERANALYSIS&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1773420645746');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='1016px';vizElement.style.height='991px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>


---

## 🔎 Key Analysis Steps
1. Data cleaning and handling missing values
2. Distribution analysis of price
3. Correlation analysis (reviews vs price)
4. Feature scaling for clustering
5. KMeans clustering to identify listing patterns
6. Spatial mapping of average price by neighborhood

---

## 📊 Key Insights
- Nightly prices are strongly right-skewed (few premium outliers)
- Reviews and price show near-zero linear correlation
- Minimum nights moderately negatively correlated with reviews per month
- Clear geographic pricing variation across neighborhoods
- Emerging question: Do premium pricing patterns align with neighborhood equity indicators?

---

## 📁 Repository Structure


---

## 🚀 Next Steps
- Perform statistical testing on neighborhood price differences
- Incorporate health equity index data
- Develop regression modeling
- Build an interactive dashboard

---

## 👩‍💻 Author
Mary Kane  
Operations & Data Analyst  
Bilingual (English–Spanish)
