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
    font-size: 2.2em;
    margin-bottom: 0.7em;
}

h2 {
    font-size: 1.8em;
    margin-bottom: 0.7em;
}

h3 {
    font-size: 1.5em;
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

/* Add Power BI Dashboard styles */
.powerbi-container {
    width: 100%;
    max-width: 1140px;
    margin: 20px auto;
    overflow: hidden;
    position: relative;
    padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
    height: 0;
}

.powerbi-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
}

/* Responsive adjustments for Power BI */
@media screen and (max-width: 768px) {
    .powerbi-container {
        padding-bottom: 75%; /* Slightly taller on mobile */
    }
}

/* Company description styles */
.company-description {
    font-size: 1rem;
    font-weight: normal;
    margin-bottom: 1em;
    color: #333;
}

/* Professional Experience styles */
.professional-experience p {
    font-size: 1rem;
    font-weight: normal;
    margin-bottom: 1em;
    color: #333;
}
</style>

## Technical Analyst

📍 Hungary, Europe

<p class="company-description">Hey, I'm Anoosha. I am a Technical Support Analyst and Senior Support Specialist with 4+ years in leading multinational firms in growing their working EcoFlow | Ex-Financial Analyst @ Ittefaq Group | Ex-Senior Support Specialist @ Fossil Group Inc. | Operation Team Leader | Customer Service Sales Specialist | BBA @ UoD (1st Class Honours)</p>
---

### Education

| Degree | Institution | Year |
|:------:|:----------:|:----:|
| BSc., Business Administration and Management | University of Debrecen | 1st Class Honours 
| Cambridge International A Level Examination | LGS | A*, A, B

---

### Skills

* **Core Competencies**: IBM, SPSS, SAP, SQL, Tableu, Salesforce, Microsoft Suite, Excel, Spreadsheets, CRM, ERP, Power BI.

* **Soft Skills**: Verbal Communication, Compassionate, Multi-tasking, Result Oriented, Organised, Issue Resolving, Teamwork, Detail Oriented.

---
### Key Achievements

* Resolved 120+ hardware/software issues daily for US and Canada clients using CRM/ERP platforms, boosting system reliability and user satisfaction by 90%. Consistently maintained 90%+ SLA/KPI adherence, and supported over $200K+ worth of customer operations with high efficiency and technical precision as Technical Support Analyst @ EcoFlow.

* Negotiated vendor contracts and optimized procurement workflows, achieving 20% budget saving (approximately $50K). Maintained 100% financial record accuracy, reduced reporting errors by 10%, and streamlined payment operations using Moneris and Authorize.Net, cutting operational costs by 10% while contributing to 20% improvement in HR efficiency and employee satisfaction as Financial Analyst @ Ittefaq Brothers.

* Customized Salesforce dashboards and Power BI tools, resulting in 12% increase in sales targets and 22% growth in lead conversions. Supervised 25+ employees to drive 15% improvement in productivity, processed 100+ orders weekly via SAP and CyberSource, reducing errors by 50% and boosting order fulfillment speed by 15%, while improving operational reporting efficiency by 10-20%, supporting over $150K+ in order management and supply chain workflows as a Seasonal Operations Team Leader & Senior Support Specialist @ Fossil Group.

* Streamlined SAP order management systems and enhanced client servicing through CRM platforms, cutting order processing errors by 50%, increasing order fulfillment speed by 15%, and improving overall operational efficiency by 10-20%, safeguarding more than $150K+ worth of supply chain and customer operations through targeted system improvements being a Senior Support Specialist @ Fossil Group.

---
### Featured Publication

<p class="company-description">Signaling and Screening in Employee Selection: Skill, Education, or Experience</p>

<p class="company-description">Featured in the Open Journal System (OJS) at Debreceni Egyetem, that hosts the top 5% publications on business, economics, and management sciences.</p>

<img src="./assets/img/publication.png" class="project-image" alt="Publication">

* **Description**:This  study  examines  the importance of three factors—abilities, work experience, and education—that serve as indicators and filters in the selection process. It aims to determine how current job market entrants perceive the importance of these three factors from the perspective of employers.

* **Key Findings**: The key finding is that respondents consider skills to be the most important, followed by experience, with education playinga secondary role


<img src="./assets/img/publication-table.png" class="project-image" alt="Publication Table">

<hr class="project-separator">

---

### Professional Experience

**Technical Support Analyst and Operations Specialist @ Ecoflow (October 2023 - Present)**  
<p class="company-description">EcoFlow serves 4.5M+ customers across 100+ countries, with $1B+ valuation, nearly $1B revenue, 1,200+ employees, and award-winning innovations like TIME's "Best Inventions of 2021.</p>

**Financial Analyst @ Ittefaq Group (Jun 2023 - Sep 2023)**  
<p class="company-description">Ittefaq Group, a leader in the construction and steel industries has annual revenue of $100+ million with 1000+ employees. The company's commitment to quality and innovation has solidified its reputation as a key player in construction sector.</p>

**Seasonal Operation Team Leader @ Fossil Group (Mar 2023 - Sep 2023)**  
<p class="company-description">Promoted to Team Leader</p>

**Senior Support Specialist @ Fossil Group (Sep 2022 - February 2023)**  
<p class="company-description">Fossil Group, Inc. operates in 140+ countries with 30,000+ distribution points, $1.4B+ revenue, 6,000+ employees, and leads global fashion with brands like Michael Kors, Diesel, BMW, and Emporio Armani.</p>

**Operations Intern @ WWF (Jun 2017 - Aug 2017)**  
<p class="company-description">WWF is one of the world's largest conservation organizations, active in over 130 countries with 5 million+ supporters. With annual revenues over $350 million, it leads global efforts in wildlife protection, habitat conservation, and climate change advocacy.</p>

* **Responsibilities** 
* Coordinated logistics for 15+ city-wide food drives, ensuring timely collection and distribution of 10,000 € of food.

* Managed partnerships with 100+ businesses to secure food donations, optimizing supply chain processes for efficiency.

* Led a team to win 1st place out of 50 teams by driving operational excellence and exceeding target goals.

* Documented and analyzed food conservation impact, influencing 50,000+ individuals through targeted awareness campaigns.

* Maintained high operational efficiency and team morale, ensuring smooth event execution under tight deadlines.



---

### Awards & Honours

* **Dean's Honour List** 
  4.67/5 GPA in Business Administration BSc.

* **WWF** 
  Built 12 Hand Gesture Controlled Robotic Vehicles

---

### Extracurriculars

* **Tech Speaker Innovia UK Women in STEM**  
  Keynote Guest Speaker.    

* **Actor, Dramatics**
  3 Theatrical Performance for 5000+ audiences.


---

### Contact

* **LinkedIn**: [Anoosha Tariq](https://www.linkedin.com/in/anoosha-tariq-sahi){:rel="noopener noreferrer"}
* **Email**: anooshy10@gmail.com

---

_This portfolio is constantly updated with new analyses. Check back regularly for updates!_
