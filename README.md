# Interactive Excel Dashboard on Performance Analysis of Students

<br>
<p align="center"><img src="Media Files/assessment-analysis.png" width="600" height="400">

</p>

## 📝 Description
 </h2>
<p>
<animated-image data-catalyst="" style="float: right; width: 400px;">
<a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/190338430fb2eca4d172a1987205c5e073b2de72db46cb4ed12cf1c2fa32041a/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f645765734263544c61766b5a754733354d492f67697068792e676966" data-target="animated-image.originalLink">
<img align="right" alt="Coding" height="200" width = "310" src="Media Files/analysis.png" data-canonical-src="Media Files/analysis.png" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage">
</a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play Coding"></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play Coding">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open Coding in new window" class="AnimatedImagePlayer-button" href="https://camo.githubusercontent.com/190338430fb2eca4d172a1987205c5e073b2de72db46cb4ed12cf1c2fa32041a/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f645765734263544c61766b5a754733354d492f67697068792e676966" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></p>
      
 - This repository represents **"An in-depth analysis of the performance of students of my school (JNV Baghpat) in secondary school examination through pivot tables and Interactive Excel Dashboard"**  
 - It also helps analyze the status of admission of these students to Senior Secondary
 - With the help of this project we can get useful insights into the performance of students which can eventually help the school taking important decisions for the ultimate good of students

## ⏳ Dataset
* Data of 83 students of my school has been used
* Result Analysis data prepared in Excel using functions and formulae
* Final sheet was prepared in same workbook using cell referencing, VLOOKUP and INDEX-MATCH functions
* Download the excel file: https://github.com/dipeshbhatt1/Excel-Project/blob/main/Dataset%20%26%20Dashboard/cbse-result-analysis.xlsx

## 🏽‍ Download the Dashboard:
- Download the Dynamic Excel Dashboard file: https://github.com/dipeshbhatt1/Excel-Project/blob/main/Dataset%20%26%20Dashboard/cbse-result-analysis.xlsx

## <img src="Media Files/steps.png" width="45" height="40"> Steps Involved

1. **Objective:** To perform an in-depth analysis of the CBSE Board result of students of my school to draw insights to make Annual Plan for the ongoing academic year accordingly
2. **Data Collection:** Data of 83 students was taken into account along with CBSE result data for Class X 2023 i.r.o. of my school
3. **Data Modification and Organisation:** Initially the raw data had multiple locations in just one column, a similar situation was with skills too. This was because for a particular job opening the employer may provide more than one location option to candidates, and these days a single skill is not enough to enter a job in the corporate sector. So, two separate datasets for location and skills were created using the explode() function in pandas. After applying techniques like Data Cleaning (imputation, and removing duplicate records), EDA, and Feature Generation, a total of 4 datasets were generated, which were used to perform aggregations on MySQL and visualization was done on PowerBI by creating attractive dashboards. In the whole analysis the main features or details involves are mentioned below:
```bash
    designation
    job location
    industry hiring for
    desired skills
    desired experience
    name of the company (employer)
    establishment year of the company
    company size
    ratings for the company by employees on various factors
```
4. **Data Analysis and Visualisation:** All four datasets were imported on MySQL Workbench, created relations using primary key-foreign key combinations, and some inciteful aggregations were performed. Then the same datasets were also imported on PowerBI Desktop, relationships were created among each other, and then 3 different dashboards were created (refer to screenshots)
5. **Key Incites and Conclusions:** All the key incites and conclusions drawn are mentioned after the screenshots hereunder.

 ## Dashboard
<p align="center"><img src="Media Files/cbse-result-analysis.jpg" width="800" height="375">

## <img src="https://user-images.githubusercontent.com/108053296/185756908-fbb62168-d923-48f2-992f-b8e2fde848fe.gif" width="48" height="48" > Conclusion and Key-Insights
   
   1. Corporations or companies established more than 10 years ago are hiring more aggressively than startups
   2. Python and SQL still remain the most in-demand skills for Data Science and Analysis, followed by Machine Learning. Gone are those days when just having good knowledge of Excel was enough to aspire for the said field.
   3. Also, Python and Java are topping the list of most in-demand skills by recruiters in India
   4. Employees working with Startups have better overall experience than those working in Corporations
   5. We can see that some of the well-known companies, such as Delta, Uber, PhonePe, Jungless Games, Mahindra Insurance, etc, belonging to different company-size categories, are topping the list of overall ratings by their employees
   6. Bangalore is the topping the list, having the most number of job opportunities i.e. alomost 50%.
   7. Software Engineering is the highest recruiting industry, almost across all locations. Also, about 50% work from home job offers are given by the Software Engineering industry itself.
   8. Employees have marked better overall experience for companies with sizes 10-50 and 50-200 than all other categories which indicates that companies within these 2 categories may be better for candidates to look for.
   9. In the non-tech field - The sales and Business industry is recruiting the most

## Contributing
Contributions are always welcome!
