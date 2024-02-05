<!--
*** ReadMe written by K. Sophie Will
*** Outline credit to: https://github.com/othneildrew/Best-README-Template
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/ksophiewill/uijpdv">
    <img src="logos/UIJP_logo2.jpg" alt="UIJP Logo" width="250" height="150">
    
  <a href="https://github.com/ksophiewill/uijpdv/tree/main/logos">
    <img src="logos/APF-Logo-v2.jpg" alt="APF Logo" width="250" height="150">
  </a>
<br />
<div align="center">
  <a href="https://github.com/ksophiewill/uijpdv/tree/main/logos">
    <img src="logos/sltrib.png" alt="SLTrib Logo" width="400" height="60">
    </a>

<h3 align="center">Domestic Violence-Related Charges in Utah State Courts</h3>

  <p align="center">
    Utah District and Justice Court data from the Utah State Courts, as seen in the Utah Investigative Journalism Project's domestic violence in the courts series published by the Salt Lake Tribune and supported by funding from the Alicia Patterson Foundation and the Fund for Investigative Journalism.
    <br />
    <br />
    <a href="https://github.com/ksophiewill/uijpdv"><strong>Explore the data »</strong></a>
    <br />
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<div align="left">
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    <li><a href="#guide-to-this-project">Guide to this Project</a>
      <ul>
        <li><a href="#data-dictionary">Data Dictionary</a></li>
        <li><a href="#faq">FAQ</a></li>
      </ul>
    <li><a href="#use">License</a></li>
    <li><a href="#contact-and-credit">Contact and Credit</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About the Project

Throughout 2023, K. Sophie Will and Eric S. Peterson of the Utah Investigative Journalism Project acquired records of nearly a quarter of a million charges filed in Utah State Courts relating to domestic violence covering Dec. 1, 2013 to Nov. 30, 2023. From Sophie's data analysis, Sophie and Eric wrote a series on the state of domestic violence in Utah courts, released in early 2024 by the Salt Lake Tribune, supported by funding from the Alicia Patterson Foundation and the Fund for Investigative Journalism. 

In this repository you will find the clean data for both Justice and District courts, as well as a data memo with our findings. Please don't hesitate to reach out to Sophie with any questions, her contact information can be found below.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Built With

In an effort to make our data as accessible as possible, this project was done using Excel and SQL. Files are provided in .xlsx and .csv format.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ROADMAP -->
## Guide to this Project

- [ ] Data
  - [ ] District Master (in .xlsx and .csv) is the raw and cleaned data of every charge relating to domestic violence filed in District Courts in the time frame.
  - [ ] Justice Master (in .xlsx and .csv) is the raw and cleaned data of every charge relating to domestic violence filed in Justice Courts in the time frame.
    - NOTE: The Justice Master .csv file had to be zipped due to its size.
- [ ] Data Analysis
  - [ ] UIJP Data Memo is a .pdf of the case analysis done on the raw data, grouped by cases, from both courts. It includes numbers on the total charges and cases, the proportion of cases to the population, case severity, whether the case was related to domestic violence at its disposition, filing year, sentencing year, verdict, per court, dismissals per court, the severity of those dismissed and dismissals by urban and rural areas.
  - [ ] District Data Analysis and Justice Data Analysis are Excel workbooks containing the tables in the data memo for ease of use.
  - NOTE: This analysis was done by grouping charges into their cases, so when describing these findings, use the wording "__ number of cases include at least one charge that __."
  - NOTE: District data was compiled by county, Justice data remained on the court level.
    
<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Data Dictionary
- Unique_ID: A unique identifier for each case and every charge with this number belongs in the same case.
- Case_ID: A case identifier as determined by the jurisdiction, may repeat on a statewide scale.
- Court: Where the charge was filed.
- Filing_Date: The full date the charge was filed.
- Filing_Month: The month the charge was filed.
- Filing_Day: The day the charge was filed.
- Filing_Year: The year the charge was filed.
- Official_Violation_Code: The code for the charge in Utah law.
- Charge: The name of the offense.
- Severity: What level of charge. 
- Verdict: The decision of the court on the charge.
- Sentence_Date: The full date the charge was sentenced.
- Sentence_Month: The full date the charge was sentenced.
- Sentence_Day: The full date the charge was sentenced.
- Sentence_Year: The full date the charge was sentenced.
  - NOTE: There are "nones" found in the sentencing columns, indicating that in the raw data there was no sentencing date provided when the data was obtained.
- DV at Disposition: There are three options: "DV at Disposition" meaning the criteria for the case being DV were still present when the charge was disposed; "Not DV at disposition" meaning the criteria for the case being DV were removed through the course of the case; or "Not disposed" - the charge hasn't been adjudicated yet and the determination couldn't be made.
  
<p align="right">(<a href="#readme-top">back to top</a>)</p>

### FAQ
These will continually be updated.
- Q: In the data analysis, under population proportion, several courts have empty cells for the population markers. Why?
  - A: These areas have less than 5,000 people as per the 2020 Census.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- STORIES -->
## Stories

- [ ] [Utah’s domestic violence crisis has gotten worse after a change meant to help victims](https://www.sltrib.com/news/2024/02/05/utahs-domestic-violence-crisis-has/) 
- [ ] More stories are still coming! Keep an eye on the Salt Lake Tribune for our full series in the coming weeks.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## Use

The data may be forked or otherwise duplicated with credit given to the Utah State Courts and the Utah Investigative Journalism Project. 

To use the files outside of GitHub, simply download the raw file.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact and Credit

K. Sophie Will - Data Reporter - [@ksophiewill](https://twitter.com/ksophiewill) - ksophiewill@gmail.com - [ksophiewill.com](https://ksophiewill.com)

Eric S. Peterson - Editor, Reporter -[@UTInvestigative](https://twitter.com/UTInvestigative) - epeterson@utahinvestigative.org - [utahinvestigative.org](https://www.utahinvestigative.org/)

Project Link: [https://github.com/ksophiewill/uijpdv](https://github.com/ksophiewill/uijpdv)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

