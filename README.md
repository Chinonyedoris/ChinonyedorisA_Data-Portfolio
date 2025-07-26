# | Data Analyst• |UX Researcher | Developer|• AI Enthusiast 
# Short Tagline |Database Management |Administrator | Aviator | UX Researcher & Product Designer | Data & Design

    Hi, I’m Chinonye. Welcome to my portfolio."Highly driven in AI (Artificial Intelligence)with strong proficiency in machine learning,      NLP(Natural Language Processing), deep learning,     and data-driven problem solving .I’m interested in web development, data             science, and open-source contributions. I’m currently learning React, Node.js, and machine learning. I’m looking to collaborate on        open-source projects and hackathons. I love exploring new technologies! 
    I’m passionate about applying AI to solve complex challenges in industries such as development and deployment of large Language           models (LLMs), finance, healthcare, logistics, and tech. With a continuous learning mindset and a deep understanding of data              infrastructure, I aim to bridge the gap between raw data and actionable intelligence.
    I design intuitive digital experiences and solve real-world problems using AI, UX, and data. Welcome to my digital portfolio              showcasing key projects in data analysis, UX research, and AI integration. With a background in Geological Sciences and professional      experience in aviation data and administration, I bring a unique lens to technology—merging logic, research, and design to solve          global problems.

# PROJECT Portfolio 
    Data, Design & Innovation
    AI, UX/Product Design, and Data."

# Professional Bio":
  Motivated and versatile Professional with a strong foundation in web development, data analysis, administration, database management,     artificial intelligence and UI/UX design. Passionate about building clean, user-focused applications and contributing to the open-        source community. Adept at using modern frameworks, solving complex technical problems, and collaborating across global teams.            Currently advancing skills in React.js, Node.js, and Machine Learning. Open to Looking to collaborate on open-source projects, web        apps, and AI tools.
  I'm a passionate and creative Data Analyst and UX Researcher, deeply driven With experience across aviation analytics, UX design, and     data annotation for AI, I strive to create meaningful digital solutions that improve lives. I'm a lifelong learner with a love for        clean design, structured data, and building community-centered platforms.

# Mission
   As a passionate creative, researcher, and solutions-driven individual, my commitment to Africa lies in empowering lives through innovation, technology, and storytelling. I aim to build digital platforms that foster youth expression, education, and entrepreneurship. I actively engage in writing, UX design, and data analysis to address systemic issues and offer    transformative ideas. Through continuous learning, collaboration, and community outreach, I intend to mentor, inspire, and uplift future African leaders while promoting values of purpose, resilience, and integrity. My mission is to ignite change—spiritually, intellectually, and socially—across generations.
   
# Technical Skills
    • Languages & Frameworks: HTML, CSS, JavaScript, Python, SQL, React (learning), firebase,
      Node.js (learning)
    • Tools & Libraries: Git, GitHub, Figma, Pandas, NumPy, Canva, CapCut, Power BI, Video Editing & 3D Animation
    • Databases & Data Tools: Excel (Advanced), SQL, Google Sheets, Power BI
    • Collaboration & Project Management: Trello, Notion, Slack, Zoom, Google Workspace, Mi
      crosoft Outlook.
    • Design: UI/UX (Figma), Wireframing, Visual Branding
    • Others: SEO Tools (Yoast, SEMrush), Tableau, Adobe Suite, CapCut

# Trainings & Workshops
    • Harvard University– Artificial Intelligence with Python — Coursework — Training — search al
      gorithms, knowledge representation, neural networks, and reinforcement learning using Python —
      Building intelligent systems and implementing AI concepts.
    • AltSchool Africa– School of Data Data Analysis Program — Excel, SQL, Power BI, Python.
    • AWS Cloud Computing Bootcamp– CloudSec Network —Fundamentals of AWS.
    • She Leads Africa Bootcamp — Digital Marketing, Video Editing, and Content Creation — Brand
      Growth.
    . 🗓️ Bootcamp: Data Analytics Track – Quantum Analytics June 2025 Cohort.
    . 2025 Global Africa Workforce Summit.
    . The Mosart Academy of art Training.(Short-term 10.2 art Course Graduant).
    • TechyJauntUI/UXDesignBootcamp—User-CenteredDesign, Wireframing, Prototyping (Figma)figjam.
    • WHXWorld Health Expo (Training Attendee) — Workshops on global health innovation.
    • Propel — Jobberman Soft-Skills Training —Professional communication, teamwork.
    • HNG11 Internship Training Institute — Data Analyst Intern.
    • ALX Virtual Assistant Training Program.
    
# 🎓 Ongoing Learning

Bootcamps: AWS Cloud Computing at CSN Network, UX at Techy Jaunt

Weekly hands-on projects, EC2 instance provisioning, UX wireframes

# Publications & Journals
     . Flood Risk Monitoring Using Twitter Data, collecting Twitter Data For Social Media Analysis.
     . An Overview of Global Social media Usage.
     . ATA AFRICA MEET & GREET EVENT BUSINESS PROPOSAL PLANNING.
     . CREATIVE PORTFOLIO ARCHIVE PRESENTATION MULTI FORMAT PORTFOLIO ARCHIVE FOR CONTENT CREATORS: UX RESEARCH & PRODUCT REFINEMENT.
     . AN ARTICLE RESEARCH WRITING ON LIFESTYLE OF LAGOS.
     . TRACK DATA ANALYSIS TECHNICAL REPORT ON TITATIC PASSENGER LIST.
     . A CULTURAL EXCHANGE AND TOURISM PROGRAMME BUSINESS PROPOSAL WRITING.
     . NIGERIAN ECONOMIC DATA 1993-2025.
     . NAIRALAND AND NRC WEBSITES UX RESEARCH.
     . A WRITTEN ESSAY ON SOCIAL TECHNICAL DYNAMICS.
     . THE HISTORY OF COVID-19 RESEARCH DOCUMENT.
     . RESEARCH & PROPOSAL PROJECT REPORT: LEVERAGIING DATA ANALYTICS TO OPTIMIZE SUSTAINABILITY IN INFRASTRUCTURE.

# AWS Bootcamp Week 6 – Metabase Deployment with ECS & RDS

This repository documents my Week 6 project for the CloudSec Network AWS Bootcamp, where I successfully deployed **Metabase** using **Amazon ECS (Fargate)** and connected it to a **PostgreSQL RDS** database.

---

## 🚀 Project Overview

- **Objective:** Deploy Metabase container on AWS ECS with Fargate, and connect it to a PostgreSQL RDS instance.
- **Goal:** Demonstrate ECS + RDS communication, secure networking setup, and functional data visualization using Metabase.

---

## 🧱 Tech Stack

- **Amazon ECS (Fargate)**
- **Amazon RDS (PostgreSQL)**
- **Docker**
- **CloudWatch**
- **IAM Roles**
- **Security Groups / VPC**

---

## 🔧 Setup Steps

### 1. Create PostgreSQL on RDS
- Engine: PostgreSQL
- Port: `5432`
- Public Access: No
- Security Group: Accepts inbound traffic from ECS task

### 2. Create ECS Task Definition
- Image: `metabase/metabase`
- Port Mappings: `3000`
- Environment Variables:
  - `MB_DB_TYPE=postgres`
  - `MB_DB_DBNAME=[your-db-name]`
  - `MB_DB_PORT=5432`
  - `MB_DB_USER=[your-username]`
  - `MB_DB_PASS=[your-password]`
  - `MB_DB_HOST=[your-RDS-endpoint]`

### 3. Configure Fargate Service
- Launch Type: Fargate
- Cluster: ECS Cluster
- Security Group: Allow `3000` inbound from your IP or Load Balancer

### 4. Verify Deployment
- ECS logs confirm container is running
- Metabase accessible at: `http://<PUBLIC-IP>:3000`
- Successful connection to RDS database

---

## 📸 Screenshots

- ECS Task & Service Running
- Security Group Inbound Rules (Port 3000 & 5432)
- RDS Instance Running
- Metabase Web UI (Login Screen)

---

## 📍 Author

**Chinonye Doris Aniagolu**  
💼 UI/UX | Cloud | Data | DevOps  
🔗 [Portfolio](https://chinonyedoris.github.io)

# ✅ PROJECT TITLE: (OneLink)A Unified Portfolio & Publishing Platform for Creators

## 📘 PROJECT DESCRIPTION:
OneLink is a modern, user-centric digital platform that enables creators to combine their portfolio, publishing work, and digital presence under one single profile. The product emerged from identifying pain points creatives face in managing content, building an audience, and growing visibility online.

It allows users to upload unlimited content, publish blog-like articles, gain followers, and track engagement analytics — all in one place. With a smooth, micro-interactive UI and responsive design, OneLink offers a seamless experience across mobile, tablet, and desktop devices.

The project was developed during the TechyJaunt UI/UX Designer Bootcamp, focused on building end-to-end product design skills, from user research to interactive prototyping.

### 🎨 STYLE GUIDE: OneLink Design System
# 🔵 Color Palette:
Name	Use Case	HEX Code	Example
Primary Blue	Buttons, CTAs, Highlights	#3A8DFF	Follow Button
Light Blue	Backgrounds, Hover States	#E6F0FF	Card Hover
White	Main background	#FFFFFF	Page BG
Dark Grey	Headings, Text	#2C2C2C	Page Titles
Medium Grey	Subtext, Icons	#6E6E6E	Descriptions
Success Green	Confirmation/Success	#1DB954	Post Published
Error Red	Errors, Alerts	#FF4C4C	Invalid Inputs

## ✒️ Typography:
Element	Font	Weight	Size
Heading 1	Poppins	Bold	32px
Heading 2	Poppins	Semi-Bold	24px
Body Text	Inter	Regular	16px
Caption/Hint	Inter	Light	12px

## 🧱 Components & States:
# ✅ Buttons:
Primary Button: Blue BG, White Text, Rounded (8px)

Secondary Button: White BG, Blue Border, Blue Text

Disabled: Grey Text & Border, Light Grey Background

# 🪪 Cards:
Rounded corners (12px)

Drop shadow (rgba(0, 0, 0, 0.08) at 4px)

Includes: title, subtitle, image, action icons

# 🏷️ Tags:
Soft background color

Rounded Pill Shape

Small font size (12px), e.g. #UI/UX, #Design, #Content

# 🔁 States & Micro-Interactions:
Hover States: Slight lift (transform: scale(1.02)), soft shadow

Follow Button: Changes to "Following" with smooth slide transition

Upload Progress Bar: Animated loader with success checkmark

# 🛠️ PRACTICAL GUIDE FOR USING STYLE GUIDE:
🔹 1. Consistency is Key
Use the defined color codes strictly — e.g., don’t mix unapproved blues or greys.

🔹 2. Spacing Rules
8pt Grid System

Cards: Padding 16px

Sections: Margins 32px between major blocks

🔹 3. Accessibility Tips
Ensure contrast ratios (Blue on White = pass)

Text minimum size = 16px

Avoid full red for errors without icon cues

🔹 4. Mobile Adaptation
Collapse nav into hamburger

Cards become vertical stacks

CTA buttons stretch full width

## Article Writing UX Design Project: ✨ Designing Connection: My Journey Creating a Multi-Format Content Sharing App

By [Chinonye Doris Aniagolu] | UI/UX Designer | Techy Jaunt Cohort 6 Bootcamp

### A well-written storytelling-style Medium case study post(https://medium.com/@chinonyedorisaniagolu/case-study-2a17e953a05c)

## 🚀 Portfolio Deployment Complete! 🌐
I'm excited to share that I have successfully deployed my AWS Bootcamp Deliverables in a live, organized portfolio website hosted on GitHub.
🔗 Visit Portfolio(https://chinonyedoris.github.io/AWS-Bootcamp-Submission-Portfolio-ChinonyeAniagolu/)

### 💼 Project Highlights:
✅ Compiled and documented all weekly tasks in a clear, structured format
✅ Configured a custom GitHub repository for deployment
✅ Deployed using GitHub Pages with working links, screenshots, and walkthroughs
✅ Included security and provisioning tasks (like EC2 setup, RDP, IAM, etc.)

📌 This was a one-time, all-in-one project portfolio setup as required by the AWS Cloud Bootcamp—and I'm glad to have completed it successfully.


# 💼 Total Sales Computation – Excel Project

## 📌 Project Overview
This project demonstrates how to compute **Total Sales** in an Excel dataset by applying fundamental Excel functions and relative referencing. It was completed as part of the Quantum Analytics June Cohort – Data Analyst Track.

## 🎯 Goal
To compute the **Total Sales** for each product entry using the formula: Total Sales = Sales Price × Quantity Sold

## 🛠️ Tools & Technologies
- Microsoft Excel  
- Relative and Absolute Referencing  
- Excel Formulas: `SUM`, `COUNT`, `COUNTA`, `COUNTBLANK`, `MIN`, `MAX`, `AVERAGE`  
- Paste Special (Values, Formats, Formulas)  
- Transpose Function

## 🧮 Methodology
1. **Dataset Columns**:  
   - Product Name  
   - State  
   - Sales Price  
   - Quantity Sold  

2. **Data Operations**:  
   - Used **relative referencing** to multiply `Sales Price` and `Quantity Sold` to compute `Total Sales`.  
   - Applied the formula in the Total Sales column and used drag-fill to apply it to the rest of the rows.  
   - Used `SUM` to calculate total revenue across all entries.  
   - Used `MIN` and `MAX` to determine the range of values for unit price and total sales.  
   - Applied `COUNT`, `COUNTA`, `COUNTBLANK` to determine data structure and completeness.

3. **Formatting & Cleaning**:  
   - Applied **Paste Special** to isolate formulas, values, and formats.  
   - Used **Transpose** to restructure data as needed.

## 📈 Key Outputs
- ✅ Computed total sales for each row
- ✅ Aggregated revenue and sales statistics
- ✅ Identified min/max pricing and volume insights
- ✅ Cleaned and formatted dataset for readability

## 📚 Skills Demonstrated
- Spreadsheet computation and logic building  
- Data cleaning and structuring  
- Analytical thinking using Excel tools  
- Understanding of referencing and automation in formulas

# 📈 Excel Data Analysis: Sales Report Using Basic Functions

 ## 🎯 Objective:

- To analyze a dataset containing Unit Price and Sales Price for different products (Product A and B) using Excel’s      basic statistical and referencing functions. The goal was to compute:

- Total & Average Unit and Sales Prices

- Count of Columns & Rows

- Maximum Unit Price

- Minimum Sales Price for Products A and B

# 🧰 Excel Functions Used:

## Function	Purpose

=SUM(range)	Calculated total unit prices and total sales prices
=AVERAGE(range)	Found the average unit price and average sales price
=COUNT(range)	Counted all numeric (filled) entries in a column
=COUNTA(range)	Counted all non-blank cells, including text
=COUNTBLANK(range)	Identified blank/missing data for cleaning
=COLUMNS(range)	Determined number of variables/fields
=ROWS(range)	Counted total records/data entries
=MAX(range)	Found the highest unit price
=MIN(range)	Found the lowest sales price of each product

# 🧪 Problem Solved:

## Using these formulas:

✅ Total Unit Price → =SUM(Unit_Price_Column)

✅ Total Sales Price → =SUM(Sales_Price_Column)

✅ Average Unit Price → =AVERAGE(Unit_Price_Column)

✅ Average Sales Price → =AVERAGE(Sales_Price_Column)

✅ Number of Columns → =COLUMNS(Table_Range)

✅ Number of Rows → =ROWS(Table_Range)

✅ Maximum Unit Price → =MAX(Unit_Price_Column)

✅ Minimum Sales Price (Product A & B) →

## For Product A: =MIN(IF(Product_Column="A", Sales_Price_Column))

## For Product B: =MIN(IF(Product_Column="B", Sales_Price_Column)) (as an array formula or with FILTER function in Excel 365)

## 🔍 Insights Gained:

Identified pricing patterns across products

Detected missing values using COUNTBLANK

Practiced conditional logic (filtering by product)

Strengthened understanding of Excel's statistical tools for Business Analytics.

# 📊 Excel Data Analysis: Revenue Insights using Basic Functions
## Exploratory Revenue Data Analysis using Excel – Quantum Analytics 

Using absolute referencing, I successfully computed Net Salary for various employee IDs based on constant deductions across rows.
Excel functions and data cleaning techniques. The session was centered around understanding and applying Excel’s in-built formulas for data summarization and structure analysis.

## 🔧 Tools Used:

Microsoft Excel

Sample Revenue Dataset (fictitious organizational data)

## 🧠 Key Excel Functions & Outcomes:

Task: Excel Function Used	Purpose	Outcome

Identify total columns (variables)	=COLUMNS(range)	Know number of features/data points	Returned the count of columns
Count total data entries	=ROWS(range)	Understand dataset size	Returned the number of rows
Find minimum revenue	=MIN(range)	Identify lowest revenue	Displayed lowest revenue value
Find maximum revenue	=MAX(range)	Identify peak revenue	Displayed highest revenue value
Calculate total revenue	=SUM(range)	Add up total income	Returned the full sum of revenue
Count revenue entries	=COUNT(range)	Count valid revenue data cells	Counted all filled numeric cells
Determine average revenue	=AVERAGE(range)	Compute mean revenue	Showed overall average revenue

# ✅ Excel Conditional Statements – Practical Application  | Quantum Analytics
  
  I worked on a project that focused on applying conditional logic using Excel’s built-in functions.

🔧 Tasks Completed:

Used IF, AND, and OR functions to categorize data based on multiple conditions.

Applied nested IF statements to classify employees based on salary thresholds (e.g., "High", "Medium", or "Low").

Created automated decision rules to flag employees eligible for bonuses based on performance scores and tenure.

Used Conditional Formatting in combination with formulas to visually highlight rows meeting specific criteria (e.g., underperformers or top earners).

Ensured data accuracy by validating the logic with sample datasets.


📊 Key Outcome: Transformed raw data into structured, insight-driven outputs that allowed quick decision-making. These exercises deepened my understanding of how logical functions drive data filtering, analysis, and reporting in business environments.

# New Project Track Data Analysis
# "Visualizing Nigeria’s GDP Journey (1993–2025): A Business Intelligence and Data Analytics Perspective"
# Nigerian Economic GDP Data Featuring 1993-2025; A Data Analysis Approach.

# Project Introduction / Preamble
  So, I decided to embark on a personal data analytical project to draw out deep insights from Nigeria’s Gross Domestic Product (GDP)       trends. This project spans from 1993 to 2025, a critical period post-independence reflecting Nigeria’s evolving economic framework,       government reforms, and international positioning.
  I will be imploring the use of Power BI and other advanced data analytical skills—including Excel, Python, and statistical methods—to     carry out this research. The aim is not just to analyze GDP growth and decline, but to understand:
 
   When and why the Nigerian economy grew significantly

   What investments or policies contributed to such growth

   What caused declines, stagnation, or economic slowdowns

   How these trends inform scalable growth opportunities for Nigeria’s future

   This project is a blend of research, business intelligence, and economic storytelling, grounded in data. I’ll be using:

   Power BI dashboards for dynamic visualization

   Time-series and regression analysis for modeling trends

   Correlation and inferential tools to tie macroeconomic events to outcomes

# Invitation to Join the Journey
    I invite you to join me on this exciting research and business intelligence journey into Nigeria’s GDP. Whether you are a data            analyst, economist, policymaker, or simply curious about Nigeria’s economic development—this project is for you.

    Stay tuned as we uncover hidden insights, spot economic patterns, and bring data to life in the Nigerian context.

# New Project 2
# Research Proposal: Leveraging Data Analytics To Optimize Sustainability in Infrastructure
# Data Analytics and the Future of the Built Environment.
   Academic journal articles on predictive analytics, machine learning in infrastructure, and sustainable development strategies.
   Short Summary for Application Form
   This research explores the role of data analytics in optimizing sustainability in infrastructure projects. It examines how predictive     analytics and big data can enhance resource allocation, environmental impact assessments, and long-term project planning. The study       will analyze sustainability challenges in infrastructure, evaluate data-driven solutions, and develop a framework for integrating         analytics into sustainable project management. By combining literature reviews, case studies, and expert interviews, the research aims    to provide actionable insights for sustainable infrastructure development.

# Open Source Contributions & Projects
    • Firebase Installation Integration with Node.js — Node.js, Firebase CLI, Firebase Hosting, Firebase
      Firestore, Firebase Auth, Git, VS Code.
    . UX Presentation: A multi-format publishing platform Creative hub Product design Presentation.
    • UI/UX + Frontend Development — Co-designed the user interface and developed the frontend of a
      multi-format publishing platform using Figma, HTML, CSS, React,Node.js, JavaScript, and Firebase.
    • GitHub Collaborator– Fixed bugs, wrote README.md docs, and participated in open-source issue
      discussions.
    • COVID-19 Record Reformatting– Converted 200+ medical PDFs to editable formats, ensuring data
      consistency.
    • Recruitment Campaign Automation– Created job listing templates and ad visuals for talent sourcing.
 
# Certifications
    • Python 101 for Data Science– IBM, 2025
    • UI/UX Design– TechyJaunt, 2025
    • AWS Cloud Computing– CSN, 2025
    • AI Career Essentials– ALX, 2024
    • Virtual Assistant Training– ALX, 2024
    • Customer Experience & Data Analytics– HP Life, 2024–2025
    . The Mosart Academy of art Training (Short-term 10.2 Art Course) 2024
    > DataTrends Changing The Role of HR- UniATHENA, 2024

# Work Experience

# Nigerian Airspace Management Agency · Full-timeNigerian Airspace Management Agency · Full-time
# Administrative Support Associate/Flight Data Analyst
     Jan 2021 - Present · 4 yrs 6 mosJan 2021 to Present · 4 yrs 6 mos
     Lagos, Nigeria · On-siteLagos, Nigeria · On-site
         >Flight information and statistical data AnalysisFlight information and statistical data Analysis.

# Data Annotator
  # DataForce · FreelanceDataForce · Freelance
    Jul 2024 - Dec 2024 · 6 mosJul 2024 to Dec 2024 · 6 mos
    Nigeria · RemoteNigeria · Remote
        >email filtering | Saturn Collection Project
 
# HNG11 internship training 2024HNG11 internship training 2024
   Data Analyst intern
   Data Analyst intern
   HNG Tech · InternshipHNG Tech · Internship
   Jun 2024 - Jul 2024 · 2 mosJun 2024 to Jul 2024 · 2 mos
   Nigeria · RemoteNigeria · Remote


# Eauxwell Nigeria Limited · InternshipEauxwell Nigeria Limited · Internship
    Junior on-site Assistant|Front Desk officer 
    Jun 2019 - Nov 2019 · 6 mosJun 2019 to Nov 2019 · 6 mos
    Lagos, NigeriaLagos, Nigeria
    Product Sales(customer Support)On-site Supervision Product Sales(customer Support)

# Education
# Nnamdi Azikiwe University
# Bachelor of Science - BS, Geological and Earth Sciences/GeosciencesBachelor of Science - BS, Geological and Earth Sciences/Geosciences

# Licenses & certifications
   # Jobberman| Propel Learning Nigeria
     Certificate of Achievement
     Issued May 2025Issued May 2025

   # Canva Design Certification 
     CanvaCanva
     Issued Jan 2025Issued Jan 2025

# Skills:
. Data Analysis 
· SQL 
. HTML
. CSS
. PYTHON-R Programming
· UX Design 
· Figma 
· Firebase 
· GitHub 
· Research 
· Creative Writing

# 📂 Featured Projects
   . Nigerian Economic GDP Data Featuring 1993-2025; A Data Analysis Approach.
   . A Written Essay on Socio-Technical Dynamics.(Nifsy Global ltd).
   . Flood Risk Monitoring using Twitter Data.(A Research Journal).
   . NLP + geospatial analysis to detect flood-prone areas in Nigeria.
   . History of COVID-19 Medical Documentation Conversion.
   . Automated conversion and formatting of 200+ public health documents.
   . Email Filtering System for Workflow Optimization
   . Data annotation for machine learning models in productivity tools.
   . Creative Hub App UX Design
   . User research + prototyping a digital space for creatives.
   . Large Dataset Entry & Cleanup (NAMA)
   . Aviation data validation and directory management.
   . Voyage Tours Proposal Writing.
   . A Research Writing done on Lifestyle of Lagos.
   . A Research Proposal writing done on A Cultural Exchange Tourism Programme.
   . Technical Report Track Data Analysis on The Titanic Passenger List.
   . 
   

# GitHub Projects Overview"
- NAMA-Aviation-Data-Cleanup: Cleaned and validated aviation datasets; tools: Excel, SQL.
- Email-Annotation-Workflow: Labeled emails for AI categorization; tools: Label Studio.
- COVID19-Doc-Conversion-Project: Converted public health records from PDF to Word.
- Creative-Hub-UX-Case-Study: UX Design project with wireframes, research, and prototype in Figma.
- Github Personal Portfolio Website Repository
- Titanic Data Analysis Track Technical Data Report
- FireBase Web App Fire Cloud Hosting
    
#  Key Projects
     ✅ Large Dataset Cleanup for NAMA (Aviation data)
     ✅ AI-powered Email Filtering Annotation with TransPerfect
     ✅ COVID-19 Medical Documentation Archiving
     ✅ UX Design for Creative Hub App – a platform for creatives to share, collaborate, and grow
     ✅ Firebase + GitHub Web Deployment
     ✅ Personal Portfolio Website

        Each project has helped me blend my data, design, and product thinking to solve real-world challenges 🌍.

# 👩‍💻 My tool stack: 
    NodesJs.
    Figma, 
    Firebase, 
    GitHub, 
    Excel, 
    SQL, 
    Notion, 
    Python, 
    Google Workspace, and more.

# Projects & Deliverables
   # 🚀 Launched: My Data Science Portfolio Website (Placeholder)
                  📌 Repository Name: data-science-portfolio
                  🔗 Live Site: [(https://github.com/Chinonyedoris/ChinonyedorisA_Data-Portfolio/)]
                  🌐 GitHub Repo: [(https://github.com/Chinonyedoris)]

   # 🔍 About the Project
          This is my personal portfolio website showcasing projects in Data Science, Machine Learning, Data Analysis, and Research                  Writing. The portfolio was designed to reflect both technical skill and storytelling through data.
          I created this Data Science Portfolio website as a centralized space to showcase all my data-related projects — from data                 analysis and research writing to machine learning and UX case studies.

  # 🎯 Purpose:
         This portfolio acts as a placeholder and project hub, allowing me to:

         Organize and display my growing list of real-world projects

         Present my work in a structured and professional manner

          Direct potential collaborators, recruiters, or mentors to a single access point
  
   # 🧰 Built With:
                   
            HTML/CSS/JavaScript – clean and responsive UI

            Bootstrap/TailwindCSS – for mobile-friendly design

            GitHub Pages – version control and public access

   # 🎯 Goals of the Portfolio
            Showcase end-to-end data science and analysis workflows

            Highlight real-world impact and relevance

            Present projects in a digestible and visually engaging format

            Act as a central hub for recruiters, collaborators, and clients

  # 📦 Future Plans
           Add interactive dashboards using Streamlit

           Integrate blog with technical tutorials and case studies

           Deploy with custom domain

  # 📂 What It Includes:
          Placeholder sections for each project

          Links to GitHub repos and notebooks

          Coming-soon areas for detailed write-ups and dashboards

# 🛠 Upcoming:
         Individual case study pages for each project

         Blog integration for technical breakdowns

        Contact form and resume download section

This is a living space — evolving as I continue to grow and upload new work.
                   
   # 🚀 Project Launch: Successfully Deployed a Firebase-Hosted Web App with Node.js & React Integration (https://coder-896df.web.app/)
          ✅ Firebase Integration:

                   Firestore for real-time data handling

                   Firebase Authentication for secure user login

                   Firebase CLI for streamlined project setup & deployment


          ✅ Frontend Development:

                  React.js was used to build a responsive and dynamic user interface

                  Smooth routing, form handling, and UI state management implemented


         ✅ Backend Hosting & Deployment:

                   Deployed to the web using Firebase Hosting

                   Connected to GitHub for version control and CI/CD automation

                   Firebase project successfully configured with live hosting


# 🛠️ Tools & Technologies Used:

             React.js

             Firebase (Firestore, Auth, CLI)

             Node.js

            Git & GitHub
            
## 🚀 CloudSec Network Bootcamp – AWS Identity Center Setup ✅

Excited to share another milestone in my AWS Cloud Computing journey!

As part of Week 2 of the CloudSec Network Bootcamp, I successfully configured AWS IAM Identity Center (formerly AWS SSO):

🔹 Set up a new user account
🔹 Assigned permission sets using SecurityAudit policies
🔹 Tested and submitted all deliverables via screenshot validation

This hands-on task deepened my understanding of:
🔐 Identity and access management (IAM)
🛡️ Security policies and permission sets
⚙️ Administrative cloud configurations

# Amazon AMI EC2 Instance Deployment: Launched a Windows Server EC2 instance using Amazon’s AMI on a public subnet.

     Security Configuration: Created a Security Group allowing RDP (port 3389) access only from my public IP, minimizing      exposure to unauthorized access.
     
    ✅As part of the CSN CloudSec Bootcamp Week 3 task, I successfully launched and configured a Windows Server 2025 EC2       instance on Amazon Web Services (AWS). The objective was to provision a secure, publicly accessible virtual server       instance and ensure controlled RDP (Remote Desktop Protocol) access.

## ✅ AWS Bootcamp – Week 4: VPC & Subnet Configuration Achieved!

Excited to announce I successfully completed Week 4 of the CloudSec Network AWS Bootcamp, where I worked on simulating a multi-VPC architecture 🎯

🚀 Key Milestones:
🔹 Created two separate VPCs (VPC-A: 10.10.0.0/16 & VPC-B: 10.20.0.0/16)
🔹 Configured public & private subnets in both VPCs
🔹 Established VPC Peering between the two environments
🔹 Updated route tables to enable traffic flow
🔹 Captured console screenshots for validation and documentation

This hands-on experience strengthened my grasp of AWS Networking, Subnetting, and Cloud Infrastructure security. I'm one step closer to mastering AWS architecture! 🌐🔥

# 📘 Research Writing & Data Analysis
# Project Title: Flood Risk Monitoring through Social Media: A Twitter-Based Analysis

# Overview:
   This project explored the use of real-time social media data to monitor and analyze flood risks in vulnerable regions. By leveraging Twitter as a data source, the study provided    insights into how public discourse and geotagged tweets can serve as early warning signals for flood-prone areas.

# Objectives:

     Collect, clean, and analyze tweets related to flooding events.

     Identify trending flood-related keywords and hashtags using NLP techniques.

     Visualize spatial distribution of flood reports using geotagged tweet data.

     Assess the potential of social media as a real-time disaster response tool.

# Skills deployed:
     Research & Analytics

# Key Results:

     Successfully identified flood risk zones through tweet frequency and sentiment analysis.

     Created a dynamic dashboard visualizing flood-related tweets across specific Nigerian regions.

     Demonstrated the viability of integrating social media into national disaster monitoring systems.

# Contribution:
     This research offered a data-driven approach to early warning systems for climate resilience and supports smarter urban planning and emergency response policies.


# ✈️ NAMA Data Cleanup & Validation
    - Cleaned and validated aviation data for Nigerian Airspace Management Agency
    - Used Excel and SQL for organizing national reports and maintaining directories

# 📩 Email Filtering Annotation (TransPerfect)
     - Annotated thousands of email datasets to help train ML categorization systems
     - Optimized workflow using DataForce platform

# 🧾 COVID-19 Medical Documentation
     - Converted over 200+ reports from PDF to Word format with structure and accuracy
     - Supported public health archiving initiatives

# 🎨 Creative Hub UX App
     - UX case study: Research, Ideation, Prototyping in Figma
     - Built user-centered solution for creatives to share projects and collaborate
     - Tools: Figma, Miro, Google Forms

# 🌐 Portfolio Website
     - Personal portfolio built and deployed using GitHub Pages & Firebase
     - Technologies: HTML, CSS, JavaScript, Firebase

     📫 Let's Connect: https://www.linkedin.com/in/chinonyedoris-aniagolu-250603225/

# My Websites & Portfolios
     - 🔗 [LinkedIn]((https://www.linkedin.com/in/chinonyedoris-aniagolu-250603225/)
     - 🌐 [Portfolio Website](https://github.com/Chinonyedoris/ChinonyedorisA_Data-Portfolio/)
     -     My Github; (https://github.com/Chinonyedoris/)
     -     My Firebase hosting website;( https://coder-896df.web.app/)
     -     Google Developers Profile; (https:google/dev/chinonyeaniagolu)
     - ✉️ Email: ccchinonye@gmail.com
     - chinononyedorisaniagolu@gmail.com
     -{ Twitter(x)} (https://x.com/AniagoluChinon1)

---

Thanks for visiting!


  👋 Hi, I’m @Chinonyedoris  
  
## 🔗 Author
**Chinonye Doris Aniagolu**  
*Data Analyst | AI Enthusiast*  
[LinkedIn](https://www.linkedin.com/in/chinonyedoris) | [GitHub](https://github.com/Chinonyedoris)
- 👀 I’m interested in web development, data science, and open-source contributions.  
- 🌱 I’m currently learning React, Node.js, and machine learning.  
- 💞️ I’m looking to collaborate on open-source projects and hackathons.  
- 📫 How to reach me: chinonyedoris@gmail.com | [LinkedIn]https://www.linkedin.com/in/chinonyedoris-aniagolu-250603225/)  
- 😄 Pronouns: She/Her  
- ⚡ Fun fact: I love solving puzzles and exploring new technologies!
