# Hi, I'm Aki 👋
 
I'm a data and AI engineering student at Kajaani University of Applied Sciences (KAMK), based in the Tampere region, Finland. I bring 10+ years of professional experience in education.
 
I'm now moving into data engineering and applied AI. I enjoy taking messy, real-world data and turning it into something reliable and useful, and I care about clear documentation and solutions that other people can actually maintain.
 
## What I work with
 
**Data engineering:** Python (Pandas, NumPy), SQL, DuckDB, PostgreSQL, MariaDB, dbt, Bronze/Silver/Gold data modelling
**Machine learning:** scikit-learn, neural networks, object detection with YOLO and RT-DETR
**Web development:** React, Node.js, Express, REST APIs, JWT authentication
**Infrastructure:** Docker, Docker Compose, Nginx, Git, CI/CD, Linux, Proxmox, Terraform, CSC HPC (Slurm)
**Visualisation:** Power BI (DAX), Evidence, Streamlit, NiceGUI
 
## Selected projects
 
### 🚆 [Train Punctuality Monitor](https://github.com/akijharju/data-alustat)
A data platform that analyses the punctuality of trains departing from Tampere using open data from the Digitraffic API. Python ingestors load raw JSON into DuckDB, dbt builds Bronze, Silver and Gold layers with tests and documentation, and Evidence dashboards show delays and reliability trends by route.
`Python` `DuckDB` `dbt` `Evidence` `Docker` `uv`
 
### 🕳️ [Manhole Cover Detection](https://github.com/akijharju/kaivonkannet)
Object detection model for classifying manhole covers and their maintenance needs from about 10,000 images. I built a reproducible data pipeline from annotations to YOLO format and compared YOLO11 and RT-DETR. The best model reached mAP50-95 0.74, with precision 0.93 and recall 0.96.
`Python` `YOLO11` `RT-DETR` `Computer vision`
 
### 📋 [JobTrack](https://github.com/akijharju/JobTrack)
A full-stack app for tracking job applications, built on my own from start to finish. Users can save job postings, follow application status and import postings from JSON with a preview step. Includes user-specific data, JWT authentication with hashed passwords, integration tests and a containerised setup.
`React` `Node.js` `Express` `MariaDB` `Docker Compose` `Nginx`
 
### 📊 [Power BI Reporting](https://github.com/akijharju/powerbi)
Power BI coursework covering a business report, DAX measures with time intelligence and calculation groups (month-over-month change, rolling averages) and a dataflow built on Euribor interest rate data.
`Power BI` `DAX` `Power Query`
 
### 🛒 UWB Shopping Cart Analytics *(team project, code not public)*
Analysis of over 30 million rows of indoor positioning data from shopping carts. I helped build the cleaning and filtering rules and moved the data from MariaDB to DuckDB for faster analysis. Worked in a Scrum team and acted as Product Owner in one sprint.
`Python` `DuckDB` `SQL` `Scrum`
 
## Currently
 
- Studying data and AI engineering at KAMK
- Building a HomeLab data platform on my own server (Home Assistant data, PostgreSQL, dbt, local language models)
- Looking for a data engineering or data/AI internship or junior role in the Tampere region
