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
    background-color: #0077b5;  /* LinkedIn blue color */
    color: white;
    text-decoration: none;
    border-radius: 6px;
    font-weight: 600;
    transition: background-color 0.3s ease;
}

.view a:hover {
    background-color: #005e93;  /* Darker LinkedIn blue for hover */
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

### Technical Analyst

📍 Hungary, Europe

<p class="company-description">Hey, I'm Anoosha. I'm a Technical Support Analyst and Senior Support Specialist with 4+ years in leading multinational billion dollar firms in growing their customer base by atleast 20% | Saved $500K through effective cost management | Ex-Financial Analyst @ Ittefaq Group | Ex-Senior Support Specialist @ Fossil Group Inc. | Operation Team Leader | Customer Service Sales Specialist | BBA @ UoD (1st Class Honours)</p>
---

#### 📚 Education 

| Degree | Institution | Year |
|:------:|:----------:|:----:|
| BSc., Business Administration and Management | University of Debrecen | 1st Class Honours 
| Cambridge International A Level Examination | LGS | A*, A, B

---

#### 🎯 Skills 

* **Core Competencies**: IBM, SPSS, SAP, SQL, Tableu, Salesforce, Microsoft Suite, Excel, Spreadsheets, CRM, ERP, Power BI.

* **Soft Skills**: Verbal Communication, Compassionate, Multi-tasking, Result Oriented, Organised, Issue Resolving, Teamwork, Detail Oriented.

---
#### ✨ 7. Key Achievements 

1. Streamlined SAP order management systems and enhanced client servicing through CRM platforms, safeguarding more than $150K+ worth of supply chain and customer operations, being a Senior Support Specialist @ Fossil Group.

2. Optimised operational workflows through Salesforce dashboards and Power BI tools, generating  additional $20K in ARR in less than 3 months by a 12% increase in sales targets and 22% growth in lead conversions.

3. Resolved 3000+ hardware/software issues monthly for US and Canada clients using CRM/ERP platforms, boosting system reliability and user satisfaction by 90%. 

4. Supervised 25+ employees to in processing 100+ orders weekly via SAP and CyberSource, boosting order fulfillment speed by 15%.

5. Negotiated vendor contracts and optimized procurement workflows, achieving 20% budget saving (approximately $50K).

6. Consistently maintained 90%+ SLA/KPI adherence, and supported over $200K+ worth of customer operations with high efficiency and technical precision as Technical Support Analyst @ EcoFlow.

7. Maintained 100% financial record accuracy, and streamlined payment operations using Moneris and Authorize.Net, cutting operational costs by 10% @ Ittefaq Group.

---

#### 💼 Professional Experience 

**Technical Support Analyst and Operations Specialist @ Ecoflow (October 2023 - Present)**  
<p class="company-description">EcoFlow serves 4.5M+ customers across 100+ countries, with $1B+ valuation, nearly $1B revenue, 1,200+ employees, and award-winning innovations like TIME's "Best Inventions of 2021."</p>

**📌 Responsibilities** 
* Proficiently resolving customer-reported issues with CRM and ERP systems, consistently achieving over 90% in SLA and KPI adherence. 

* Diagnose and troubleshoot more than 50 hardware and software issues daily, enhancing system reliability and user satisfaction for our international clientele in the United States and Canada by 90%. 

* Facilitated cross-regional collaboration with peers, leading to a 50% increase in the rate of successful technology adaptation to meet evolving partner needs. 

**Financial Analyst @ Ittefaq Group (Jun 2023 - Sep 2023)**  
<p class="company-description">Ittefaq Group, a leader in the construction and steel industries has annual revenue of $100+ million with 1000+ employees. The company's commitment to quality and innovation has solidified its reputation as a key player in construction sector.</p>

**📌 Responsibilities** 
* Negotiated and managed vendor contracts with strategic sourcing methods, securing cost-effective procurement of IT resources, which led to a 20% budget saving. 

* This involved conducting market research, leveraging bulk purchasing, and fostering long-term partnerships to ensure competitive pricing and quality service delivery. 

* Managed up-to-date financial records with 100% accuracy overseeing both payable and receivable accounts to ensure utmost data accuracy and compliance with financial regulations, reducing financial reporting errors by 10%. 

* Spearheaded initiatives to optimize payment workflows and operations using Moneris and Authorize.Net softwares, achieving an improvement of reduced operational costs by 10%. 

* Contributed to HR administration by streamlining workflow processes, leading to departmental efficiency.

*  My support for various HR initiatives resulted in a 20% improvement in employee satisfaction. 

**Seasonal Operation Team Leader @ Fossil Group (Mar 2023 - Sep 2023)**  
<p class="company-description">Fossil Group, Inc. operates in 140+ countries with 30,000+ distribution points, $1.4B+ revenue, 6,000+ employees, and leads global fashion with brands like Michael Kors, Diesel, BMW, and Emporio Armani.</p>

**📌 Responsibilities** 
* Customized Salesforce dashboards and reports, working closely with sales teams to understand their needs and providing them with tailored tools. 

* This initiative led to a 12% increase in sales targets and improved client follow-up response times by 20%. 

* Monitored and supervised the performance of over 25 employees, implementing performance management strategies that resulted in a 15% increase in productivity while fostering a supportive and collaborative work environment. 

* Engineered Customized Salesforce, CRM and Power BI solutions to track customer engagement metrics, driving a 22% growth in lead conversion rates. 

**Senior Support Specialist @ Fossil Group (Sep 2022 - February 2023)**  
<p class="company-description">Fossil Group, Inc. operates in 140+ countries with 30,000+ distribution points, $1.4B+ revenue, 6,000+ employees, and leads global fashion with brands like Michael Kors, Diesel, BMW, and Emporio Armani.</p>

**📌 Responsibilities** 
* Mobilized SAP and Cyber Source software to manage customer request efficiently by processing of over 100 orders per week, utilizing my skills in SAP software to organize and manage customer requests efficiently. 

* These efforts led to a significant reduction in processing errors by 50%.

* Acted as a bridge between finance and sales department by initializing an average of 120+ tickets/day to resolve client requests by fetching logs and orchestrated strong client relationships via CRM. 

* Overhauled SAP order management systems, customizing functionalities to better align with business needs. 

* This resulted in a 15% increase in order fulfillment speed, and a 5% boost in supply chain efficiency. 

* Engineered SPSS to enhance reporting, analysis, aided by full-fledge individual, client reports leading to a ~20%+ increase in operational efficiency whilst managing cash-to-quote processes. 

**Operations Intern @ WWF (Jun 2017 - Aug 2017)**  
<p class="company-description">WWF is one of the world's largest conservation organizations, active in over 130 countries with 5 million+ supporters. With annual revenues over $350 million, it leads global efforts in wildlife protection, habitat conservation, and climate change advocacy.</p>

**📌 Responsibilities** 
* Coordinated logistics for 15+ city-wide food drives, ensuring timely collection and distribution of 10,000 € of food.

* Managed partnerships with 100+ businesses to secure food donations, optimizing supply chain processes for efficiency.

* Led a team to win 1st place out of 50 teams by driving operational excellence and exceeding target goals.

* Documented and analyzed food conservation impact, influencing 50,000+ individuals through targeted awareness campaigns.

* Maintained high operational efficiency and team morale, ensuring smooth event execution under tight deadlines.


---
#### 📑 Featured Publication 

<p class="company-description">Signaling and Screening in Employee Selection: Skill, Education, or Experience</p>

<p class="company-description">Featured in the Open Journal System (OJS) at Debreceni Egyetem, that hosts the top 5% publications on business, economics, and management sciences.</p>

<img src="./assets/img/publication.png" class="project-image" alt="Publication">

* **Description**:This  study  examines  the importance of three factors—abilities, work experience, and education—that serve as indicators and filters in the selection process. It aims to determine how current job market entrants perceive the importance of these three factors from the perspective of employers.

* **Key Findings**: The key finding is that respondents consider skills to be the most important, followed by experience, with education playinga secondary role


<img src="./assets/img/publication-table.png" class="project-image" alt="Publication Table">

<hr class="project-separator">

---

#### 🏆 Awards & Honours 

* **Dean's Honour List (University of Debrecen)** 
  4.67/5 GPA in Business Administration BSc.

* **Exceeding targets and operational excellency (WWF)** 
  Awarded 1st place of 50 teams in exceeding set targets and KPIs.

---

#### 🚀 Transferable Extracurriculars 

**Vice President Business Society (LGS)** 
* Led a team of 30 members to drive business-focused initiatives and enhance society growth.
* Organized 5 business events, drawing over 200 students and professionals.
* Managed event budgets, achieving a 20% reduction in overall costs.
* Led partnerships with 20+ local businesses, securing internships and mentorship opportunities for students.
* Boosted membership by 30% through strategic marketing and recruitment campaigns.

**Vice President Business Society (LGS)** 
* Led a team of 20 members, fostering innovation and collaboration in robotics projects and events.
* Organized 5+ robotics competitions, attracting over 100 participants and sponsors.
* Coordinated robotics workshops, improving student participation and skills by 40%.

---

#### 🌍 Volunteering 

**Intern (Rising Sun Institute for Special Children)** 
* Fundraised $5000 for special needs children through a 15 days door to door campaign.
* Supported over 30 children in the daily activities of special children
* Developed and tracked progress for 15 children, ensuring their developmental milestones were achieved in line with school objectives.
* Organized 20+ weekly recreational activities, boosting children’s motor skills by 10% over a 6-month period.


**Academic Support Intern (Shaheera Foundation)** 
* Assisted in teaching vocational and social skills, benefiting 30+ students.
* Utilized innovative teaching methods for teaching English and Maths, increasing student engagement by 25%.
* Provided tailored 1-1 training sessions for children with special needs.

---

#### Contact 📞

* **LinkedIn**: [Anoosha Tariq](https://www.linkedin.com/in/anoosha-tariq-sahi){:rel="noopener noreferrer"}
* **Email**: anooshy10@gmail.com

---

_This portfolio is constantly updated with new analyses. Check back regularly for updates._
