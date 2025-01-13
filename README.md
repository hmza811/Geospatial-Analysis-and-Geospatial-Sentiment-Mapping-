# Urban Population Analysis and Geospatial Sentiment Mapping

This repository contains two interconnected projects focusing on geospatial data analysis and sentiment mapping. The first project involves exploring urban and world population data, and the second centers on geospatial sentiment analysis using social media data.

---

## 1. Urban and World Population Data Analysis

This project analyzes geospatial population data to understand global urbanization trends and their implications. The key components include:

### Key Highlights:
- **Datasets Used:** Urban Population and World Population data.
- **Data Processing:** Data cleaning and exploratory data analysis (EDA) were performed to extract meaningful insights.
- **Choropleth Mapping:**
  - Urban populations in 2020 with values ≤ 67,326,569.
  - Urban populations in 2020 with values ≥ 33,100,000.
- **Trend Analysis:** Annual percentage changes in urban population from 2001 to 2021 were visualized, revealing a steady decline in growth rates:
  - Growth rates above 4% during 2001–2004 reflect rapid urbanization.
  - A decline to just above 2% by 2021 indicates urban saturation.
- **Scatter Plot Insights:**
  - Demonstrates a positive correlation between total population and urban population across countries.
  - Highlights global urbanization trends and differences in urbanization rates.

---

## 2. Geospatial Sentiment Analysis Using Social Media Data

This project focuses on mapping global sentiments and subjectivity using geotagged social media data related to ChatGPT. The analysis provides insights into regional variations in public opinion.

### Key Highlights:
- **Data Processing:**
  - Geocoding was used to map tweets to geographic locations.
  - Sentiment analysis included polarity and subjectivity analysis.
- **Choropleth Mapping:**
  - Visualized the polarity of tweets globally with positive (green), neutral (yellow), and negative (red) sentiments.
  - Subjectivity distribution maps showed regions with personal (green), neutral (yellow), and objective (blue) discussions.
- **Regional Sentiment Insights:**
  - **USA:** High tweet density in major cities (e.g., New York, San Francisco) with predominantly positive sentiments.
  - **UK:** Concentrated in urban areas like London, with a mix of positive and neutral tweets.
  - **Asia:** High positivity in countries like India and Japan, with occasional concerns about privacy and job security.
- **Actionable Insights:**
  - Positive reception globally for ChatGPT, with minimal negativity.
  - Highlights opportunities for competitors to address regional concerns and enhance AI product features.

---

## Conclusion

Both projects underscore the power of geospatial analysis in understanding trends and sentiments at a global scale:
- The **population analysis** emphasizes urbanization trends and their socio-economic implications.
- The **sentiment analysis** provides a comprehensive view of public opinion on ChatGPT, identifying opportunities and challenges for AI technologies.

---

## Technologies Used

- **Programming Languages:** Python
- **Libraries:** GeoPandas, Pandas, Matplotlib, Plotly, TextBlob
- **Tools:** Jupyter Notebook

