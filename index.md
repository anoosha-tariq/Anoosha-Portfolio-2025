---
layout: default
---

<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, shrink-to-fit=no, viewport-fit=cover">
<style>
* {
    -webkit-touch-callout: none;
    -webkit-user-select: none;
    -khtml-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    touch-action: pan-y pinch-zoom;
}

/* Base styles for consistent sizing */
html {
    overflow-x: hidden !important;
    width: 100%;
    font-size: 16px;
    line-height: 1.6;
    -webkit-text-size-adjust: none;
    text-size-adjust: none;
    -webkit-tap-highlight-color: transparent;
}

body {
    max-width: 100%;
    margin: 0 auto;
    padding: 80px 30px 0;
    font-size: 1rem;
    overflow-x: hidden !important;
    width: 100%;
    touch-action: manipulation;
    -webkit-overflow-scrolling: touch;
}

/* Project image sizing */
.project-image {
    width: 500px;
    height: 500px;
    margin: 20px auto;
    display: block;
    object-fit: cover;
    max-width: 100%;  /* Ensure images don't cause overflow */
}

.project-image2 {
    width: 500px;
    height: 500px;
    margin: 20px auto;
    display: block;
    object-fit: cover;
    max-width: 100%;  /* Ensure images don't cause overflow */
}

/* Large screens (1024px and below) */
@media screen and (max-width: 1024px) {
    html {
        font-size: 14px;
        overflow-x: hidden;
        width: 100%;
        position: relative;
    }
    
    body {
        padding: 60px 15px 0;
        overflow-x: hidden;
        width: 100%;
        max-width: 100vw;
    }
    
    .wrapper {
        overflow-x: hidden;
        width: 100%;
        max-width: 100vw;
        padding: 0 10px;
    }
    
    .project-image, .project-image2 {
        width: 450px;
        height: 450px;
        max-width: 95%;
        margin: 15px auto;
        object-fit: cover;
    }
}

/* Medium screens (768px and below) */
@media screen and (max-width: 768px) {
    html {
        font-size: 13px;
        overflow-x: hidden !important;
        width: 100%;
        touch-action: manipulation;
        -webkit-text-size-adjust: 100%;
    }
    
    body {
        overflow-x: hidden !important;
        width: 100%;
        max-width: 100vw;
        margin: 0;
        padding: 60px 15px 0;
    }
    
    .project-image, .project-image2 {
        width: 400px;
        height: 400px;
        max-width: 90%;
    }
}

/* Small screens (480px and below) */
@media screen and (max-width: 480px) {
    html {
        font-size: 11px;
        overflow-x: hidden !important;
        width: 100%;
        -webkit-text-size-adjust: none !important;
        -moz-text-size-adjust: none !important;
        -ms-text-size-adjust: none !important;
        text-size-adjust: none !important;
        touch-action: pan-y;
        -webkit-overflow-scrolling: touch;
        max-width: 100vw;
        min-height: -webkit-fill-available;
    }
    
    body {
        overflow-x: hidden !important;
        width: 100%;
        max-width: 100vw;
        margin: 0;
        padding: 60px 15px 0;
        -webkit-overflow-scrolling: touch;
        min-height: -webkit-fill-available;
        position: fixed;
        left: 0;
        right: 0;
        top: 0;
        bottom: 0;
    }
    
    .wrapper {
        overflow-x: hidden !important;
        width: 100%;
        max-width: 100vw;
        height: 100%;
        overflow-y: auto;
        -webkit-overflow-scrolling: touch;
    }
    
    .project-image, .project-image2 {
        width: 350px;
        height: 350px;
        max-width: 85%;
    }
}

/* Content sizing */
.wrapper {
    max-width: 1400px;
    margin: 0 auto;
    padding: 0 30px;
    overflow-x: hidden;  /* Prevent wrapper overflow */
}

section {
    font-size: 1.1rem;
    line-height: 1.6;
    max-width: 100%;  /* Ensure sections don't overflow */
}

h1 {
    font-size: 3em;
    margin-bottom: 0.7em;
}

h2 {
    font-size: 2.5em;
    margin-bottom: 0.7em;
}

h3 {
    font-size: 2em;
    margin-bottom: 0.7em;
}

p, li {
    font-size: 1.1rem;
    margin-bottom: 1em;
}

/* GitHub Profile Link Style */
.view a {
    display: inline-block;
    padding: 10px 20px;
    background-color: #2ea44f;
    color: white;
    text-decoration: none;
    border-radius: 6px;
    font-weight: 600;
    transition: background-color 0.3s ease;
}

.view a:hover {
    background-color: #2c974b;
}

/* Project Button Style */
.project-button {
    display: inline-block;
    padding: 8px 16px;
    background-color: #0366d6;
    color: white;
    text-decoration: none;
    border-radius: 6px;
    font-weight: 500;
    margin-top: 10px;
    margin-right: 10px;
    transition: background-color 0.3s ease;
}

.project-button:hover {
    background-color: #0245a3;
}

/* GitHub Button Style */
.github-button {
    display: inline-block;
    padding: 8px 16px;
    background-color: #24292e;
    color: white;
    text-decoration: none;
    border-radius: 6px;
    font-weight: 500;
    margin-top: 10px;
    transition: background-color 0.3s ease;
}

.github-button:hover {
    background-color: #2f363d;
}

/* Education container styles */
.education-container {
    margin: 20px 0;
}

.education-item {
    background-color: #f8f9fa;
    border-radius: 8px;
    padding: 20px;
    margin-bottom: 15px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    transition: transform 0.2s ease;
}

.education-item:hover {
    transform: translateY(-2px);
}

.education-item h3 {
    color: #0366d6;
    margin: 0 0 10px 0;
    font-size: 1.2em;
}

.education-details {
    display: flex;
    justify-content: space-between;
    align-items: center;
    color: #586069;
}

.education-details .institution {
    font-weight: 500;
    margin: 0;
}

.education-details .year {
    margin: 0;
    font-style: italic;
}

/* Desktop Styles */
@media screen and (min-width: 1250px) {
    body {
        overflow-x: hidden;
        max-width: 1400px;
    }
    
    .container {
        max-width: 1200px;
        padding: 0 2rem;
    }
    
    h1 {
        font-size: 2.5rem;
    }
    
    h2 {
        font-size: 2rem;
    }
    
    h3 {
        font-size: 1.5rem;
    }
    
    p {
        font-size: 1rem;
    }
    
    .project-image {
        max-width: 90%;
        height: auto;
    }
}

/* Medium-large screens */
@media screen and (min-width: 1024px) and (max-width: 1249px) {
  body {
    overflow-x: hidden;
    zoom: 0.9;
    -moz-transform: scale(0.9);
    -moz-transform-origin: 0 0;
  }
  
  .container {
    max-width: 1100px;
    padding: 0 2rem;
  }
  
  h1 {
    font-size: 2.3rem;
  }
  
  h2 {
    font-size: 1.8rem;
  }
  
  h3 {
    font-size: 1.4rem;
  }
  
  p {
    font-size: 1rem;
  }
  
  .project-image {
    max-width: 85%;
    height: auto;
  }
}

/* Add to the style section */
.project-separator {
    border: 0;
    height: 1px;
    background-color: #e1e4e8;
    margin: 30px 0;
    width: 100%;
}

/* Add to the style section */
table th {
    text-align: center;
}
</style>

# Data Scientist & Analyst

📍 London, United Kingdom

Hey, I'm Zanjeel. I'm a data lover and I thrive on using data for building the most innovative and latest, modern technologies. 
Here you'll find a collection of my projects in data analysis, machine learning, and artificial intelligence.

## Education

| Degree | Institution | Year |
|:------:|:----------:|:----:|
| MSc., Data Science & Analytics | Brunel University London | Dec 2024 |
| BSc., Computer Science | FAST University | Sep 2023 |




## Skills

* **Programming Languages**: Python, R, SQL, JavaScript, MATLAB
* **Data Analysis**: Pandas, PySpark, NumPy, Matplotlib
* **Machine Learning**: Scikit-learn, TensorFlow, Deep Learning
* **Data Visualization**: Tableau, Power BI, Plotly, ggplot2 
* **AI/ML**: RAG, LLMs, Speech Recognition, APIs
* **Tools**: Git, GitHub, VSCode, Google Cloud Platform

---

## Featured Projects

### 1. Voice-to-Voice LLM Assistant
<img src="./assets/img/Voice-LLM.jpeg" class="project-image" alt="Voice Assistant">
* **Description**: A conversational AI assistant that uses speech-to-text and text-to-speech capabilities, powered by Python and Google's Gemini AI. Features real-time voice recording, processing, and witty responses in real time.

* **Skills**: Python, Flask, React, Google Gemini AI, Speech Recognition, gTTS (Google Text to Speech)

* **Key Features**: Real-time voice processing, natural dialogue, witty responses, LLM

[View Live Project](https://voice-to-voice-llm.vercel.app){: .project-button} [View on GitHub](https://github.com/zanjeel/Voice-to-Voice-LLM){: .github-button}

<hr class="project-separator">




### 2. Advanced ML for Prediction in Automotive Systems
<img src="./assets/img/Data-Analysis-Using-Machine-Learning.jpeg" class="project-image" alt="Automobile Analysis">
* **Description**: Predictive analysis of automobile data using RStudio, focusing on price prediction and market trends.

* **Skills**: R, Regression, KNN, Decision Trees, Random Forests

[View Live Project](https://zanjeel.github.io/Automobile-Predictive-Data-Analysis-RStudio/Automobile-Price-Prediction.nb.html){: .project-button} [View on GitHub](https://github.com/zanjeel/Automobile-Predictive-Data-Analysis-RStudio){: .github-button}

<hr class="project-separator">




### 3. Mould Prediction for Hillingdon Council
<img src="./assets/img/Predictive-ML-Hillingdon-Council-UK.jpeg" class="project-image" alt="Weather Prediction">
* **Description**: Machine learning-based Mould prediction system developed for Hillingdon Council, UK, using various ML algorithms.

* **Skills**: Python, Tensorflow, Google Cloud Platform, LSTM, CNN, XGBoost, Time Series

* **Key Features**: Multiple ML models comparison, accurate mould forecasting, interactive visualizations

[View Live Project](https://zanjeel.github.io/Weather-Prediction-MachineLearningAlgorithms-HillingdonCouncilUK/MachineLearningModelsforWeatherPrediction.html){: .project-button} [View on GitHub](https://github.com/zanjeel/Weather-Prediction-MachineLearningAlgorithms-HillingdonCouncilUK){: .github-button}

<hr class="project-separator">




### 4. RAG-NasaAI SpaceLovers
<img src="./assets/img/NasaAI-proj-img.jpeg" class="project-image" alt="NASA AI">
* **Description**: A Retrieval-Augmented Generation (RAG) powered by vector search and LLM reasoning, optimizing knowledge retrieval and conversational AI.

* **Skills**: Astra DB, Google Gemini API, Web Scraping, RAG, AI/ML, API Integration

* **Key Features**: Real-time space data retrieval, accurate space information, interactive Q&A interface

[View Live Project](https://rag-nasaai-spacelovers.onrender.com){: .project-button} [View on GitHub](https://github.com/zanjeel/RAG-NasaAI-SpaceLovers){: .github-button} 

<hr class="project-separator">




### 5. DataAnalyserPro
<img src="./assets/img/Data-Analytics-Pro.jpeg" class="project-image" alt="Data Analysis">
* **Description**: A web-based data analysis tool that provides instant insights from Excel files without storing any data. Features rich visualizations and comprehensive statistics.

* **Skills**: Excel, React, TypeScript, Tailwind CSS

* **Key Features**: Privacy-first processing, rich visualizations, responsive design

[View Live Project](https://data-analyser-pro.netlify.app){: .project-button} [View on GitHub](https://github.com/zanjeel/DataAnalyserPro){: .github-button}

<hr class="project-separator">




### 6. Tableau Dashboards

#### Customer Insight Analysis
<img src="./assets/img/Customers-Data-Insights-Dashboard.jpeg" class="project-image" alt="Customer Insights Data Analysis">

* **Description**: Interactive dashboard analyzing customer behavior and insights with interactive filters to visualise data by sales, gender and more.

* **Skills**: Tableau, Data Visualization, Business Analytics

* **Key Features**: Interactive filters, customer segmentation, trend analysis

[View Dashboard](https://public.tableau.com/app/profile/zanjeel.tariq.sahi/viz/CustomerInsightDataAnalysis/Dashboard){: .project-button}

<hr class="project-separator">



#### Adidas Sales Analysis
<img src="./assets/img/tableau2.jpeg" class="project-image2" alt="Adidas Insights Data Analysis">
* **Description**: Data analysis and visualisation of Adidas sales in the US with interactive filters like Profit margin, product and year.

* **Skills**: Tableau, Sales Analytics, Interactive Visualization

* **Key Features**: Sales performance metrics, regional analysis, product category insights

[View Dashboard](https://public.tableau.com/app/profile/zanjeel.tariq.sahi/viz/AdidasSalesAnalaysisUSwithInteractiveFiltersforDeeperInsights/Dashboard){: .project-button}

<hr class="project-separator">


---

## Work Experience

* **President & Lead Developer @ Brunel Data Science, London (Sep 2023 - Dec 2024)**  
  * Data Science Society at Brunel is a Leading Tech organisation increasing data and tech literacy amongst students.
  * Implemented a Retrieval-Augmented Generation ETL pipeline leveraging Astra DB for vector-based storage.
  * Engineered a Python web app using JavaScript & LLMs for real-time speech recognition with sub-1s latency.
  * Led technical bootcamps for 80+ attendees per session on Python & SQL.



* **Developer  @ Risidio, London (Jan 2024 - Jun 2024)**  
  * Risido is a tech startup in London with a global client base.
  * Integrated real-time analytics into the frontend, tracking user interactions to refine UX and feature adoption.
  * Delivered directly to CEO, Stakeholders and 5+ departments on KPIs using  powerpoint presentations & Excel.
  * Streamlined data-driven decision-making by reporting and analysis 3x with Agile methodologies.



* **Data Engineer Intern @ Devsinc (Jul 2022 - Oct 2022)**  
 * Engineered a Python-based data retrieval & visualisation tool, optimizing retrieval from 20+ years of files
 * Achieved sub-0.5s query response times, allowing for rapid access to large datasets.
 * Optimized file parsing and indexing algorithms, reducing manual search effort by 70%.
 * Implemented a Python visualisation dashboard where users can visualise trends over custom time periods.



---

## Transferable Experience

* **Tech Speaker Innovia UK Women in STEM**  
  Keynote Guest Speaker.    

* **VP Robotics Society**
  Led a team of 40+ members on various robotics projects.


---

## Transferable Experience

* **Dean’s Honour List | FAST University** 
  3.8/4 SGPA in Computer Science

* **Dean's Leadership Medal | A Levels, LGS School** 
  Built 12 Hand Gesture Controlled Robots


---

## Contact

* **GitHub**: [https://github.com/zanjeel](https://github.com/zanjeel)
* **LinkedIn**: [zanjeel-tariq-sahi](https://www.linkedin.com/in/zanjeel-tariq-sahi){:rel="noopener noreferrer"}
* **Email**: zanjeel123@gmail.com

---

_This portfolio is constantly updated with new projects and analyses. Check back regularly for updates!_
