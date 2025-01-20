---
title: "Genomic Surveillance and Predictive Modelling of Mpox Virus Evolution"
date: 2025-01-20
author_profile: true
excerpt: "This project leverages artificial intelligence and machine learning to predict high-risk mutations in Mpox virus. Aimed at enhancing pandemic preparedness and assisting public health decisions in Central and West Africa."
tags: [genomic surveillance, AI, machine learning, web development, mpox, public health, healthcare]
header:
  image: "images/projects/genomic-foresight/1.png"
  teaser: "images/teasers/gf.png"
categories:
  - Data Science
  - Genomics
  - Machine Learning
  - Public Health
  - Web Development
mathjax: "true"
---

This project addresses a critical gap in Mpox virus surveillance by integrating genomic and epidemiological data with machine learning to anticipate high-risk mutations, with a focus on Central and West Africa.

### Highlights
- Developed **GenomicForesight**, a web-based platform enabling real-time genomic analysis and predictive modeling.
- Processed over **300 high-quality genomic sequences** from Nigeria and DRC.
- Built two predictive models:
  - **HighRiskPredictorInitial**: Using LSTM networks for sequential mutation analysis.
  - **HighRiskPredictorComplex**: Employing feature engineering for detailed mutation risk assessment.
- Utilized APOBEC3 mutation signatures, evolutionary impacts, and geographic distribution to calculate mutation risks.

---

### Web App Development

The **GenomicForesight** platform is a fully functional web application with the following key components:

- **Frontend**:
  - Designed using **React** for dynamic, responsive interfaces.
  - Integrated interactive data visualizations with **Plotly** to display mutation trends and risk predictions.

- **Backend**:
  - Built with **Flask**, providing APIs for real-time data analysis and model predictions.
  - Integrated with a PostgreSQL database to store processed genomic data and metadata.
  - Deployed predictive models using **TensorFlow** and **PyTorch**, enabling on-the-fly mutation risk assessments.

- **Data Processing**:
  - Backend pipelines used tools like **Pandas** and **NumPy** for preprocessing, mutation analysis, and preparing datasets for model inference.
  - Integrated bioinformatics libraries such as **MAFFT** and **IQ-TREE** for sequence alignment and phylogenetic analysis.

- **Deployment**:
  - Used **Docker** for containerization

### Features
- **Mutation Analysis**: Generate detailed insights into genomic trends, mutation hotspots, and risk scores.
- **Predictive Modelling**: Identify high-risk mutations with interactive dashboards.
- **Real-Time Reporting**: Visualizations of mutation co-occurrence, temporal trends, and evolutionary trajectories.
- **Report Generation**: Generate downloadable, detailed PDF reports summarising mutation analyses, predictive model outputs, and actionable insights.

--

Watch the demo-
<iframe width="560" height="315" src="https://www.youtube.com/embed/xBsvJR8XMrM"
frameborder="0" allowfullscreen></iframe>


### Explore More
For the full implementation and to dive deeper into the code, check out the GitHub Repository: [Here](https://github.com/CtripleU/SE_FinalYear_Capstone.git).

