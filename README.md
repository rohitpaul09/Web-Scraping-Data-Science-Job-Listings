# Web-Scraping-Data-Sciecne-Job-Listings-Python

The primary goal was to develop an intelligent tool simplifying the search for data science jobs. This involved utilizing web scraping to gather job listings from the TimesJobs website, extracting crucial details, and presenting insights through visualizations. The overall objective was to aid individuals in navigating the data science job market while keeping professionals, job seekers, and recruiters informed about industry trends.

**Web Scraping:**
The project began with web scraping job listings from the TimesJobs website. The Python code utilized the BeautifulSoup library to extract relevant details from the job listings, including job title, company name, skills required, posting time, location, and salary. The scraping process involved iterating through multiple pages of job listings, refining the extraction process, and handling diverse data structures on the website.

**Data Cleaning and Transformation:**
Following data extraction, the code applied techniques like strip() and replace() to organize the data systematically using the pandas library. Custom functions ensured a clean extraction of salary information, handling variations like 'Lacs,' and refining experience data for consistency. 

**Visualization/EDA (Exploratory Data Analysis):**
Various visualizations were created to offer insights into different facets of the data science job market:

1. **WordCloud for In-Demand Skills:**
   - **Objective:** Visualize sought-after skills.
   - **Findings:** Python, SQL, Machine Learning, and Data Mining were among the most desired skills.
<img src="https://drive.google.com/uc?id=1wmZRzNTW0Y4g3rySe8YlyR52bMKCD2Ux" alt="WordCloud" width="400" height="300">


2. **Top Cities with Most Job Openings:**
   - **Objective:** Visualize job distribution across cities.
   - **Findings:** Delhi had the highest number of job openings, followed by Bengaluru/ Bangalore, Pune, Mumbai, Hyderabad/Secunderabad, and Ahmedabad.
<img src="https://drive.google.com/uc?id=1sYc43YOovrso1CgYldAi5bZChbHLJuHO" alt="Top Cities" width="400" height="300">


3. **Comparison of Full-Time Jobs and Internships:**
   - **Objective:** Compare full-time jobs with internships.
   - **Findings:** The analysis revealed that approximately 88.0% of opportunities are full-time positions, indicating a predominant demand for full-time roles in the data science field. The remaining 12.0% consists of internship opportunities.
<img src="https://drive.google.com/uc?id=1dEavG8NoL0XBiEkmKqsrqigQbEjms7Gj" alt="Full-Time vs Internships" width="400" height="300">


4. **Top Companies Providing Internship Opportunities:**
   - **Objective:** Visualize the count of internship opportunities by company.
   - **Findings:** Maxgen Technologies emerged as the leading company providing internship opportunities.
<img src="https://drive.google.com/uc?id=1DmXPfjx-utCF4h97WufzrS_1QsWUcOh2" alt="Top Companies Intern" width="400" height="300">

5. **Comparison of Work from Home vs. On-Site Opportunities:**
   - **Objective:** Compare the distribution of work-from-home and on-site job opportunities.
   - **Findings:** Analysis of the dataset indicates that 80.0% of jobs require on-site presence, while 20.0% offer work-from-home options, as illustrated in the pie chart.
<img src="https://drive.google.com/uc?id=1fNSg8dz2mrcJ5gaXRpJ4g9-vYr7UwzVv" alt="WFH vs On-Site" width="400" height="300">

6. **Top Companies Providing Work from Home Options:**
   - **Objective:** Visualize the number of work-from-home opportunities provided by different companies.
   - **Findings:** Minanshika Softech Solution Pvt Ltd leads the list of companies offering work-from-home options, closely followed by Soumya Gayen.
<img src="https://drive.google.com/uc?id=1D-UOZVJcCwxTqDLWSMHS0gxKcueACD8B" alt="Top Companies WFH" width="400" height="300">

7. **Salary Distribution Analysis:**
   - **Objective:** Visualize the distribution of salaries.
   - **Findings:** A significant portion of salary ranges centered around 0-10 Lacs per annum, denoting entry-level pay scales, with a more pronounced concentration near 50, reflecting packages designed for experienced professionals.
<img src="https://drive.google.com/uc?id=1u0AMxKay-DhbtdUoiwtXMwZ4bLWvyF_h" alt="Salary Distribution" width="400" height="300">

8. **Experience Requirements Analysis:**
   - **Objective:** Visualize the distribution of required experience levels.
   - **Findings:** In the job market, most jobs are for beginners (0-3 yrs and 0-1 yrs experience), followed by roles needing 1-3 yrs, 5-10 yrs, 4-6 yrs experience, and more.
<img src="https://drive.google.com/uc?id=1bqAandk7IxTF-2M4NdJVb6JJxJj4RnC7" alt="Experience Requirements" width="400" height="300">

9. **Relationship Between Salary and Experience:**
   - **Objective:** Visualize the relationship between salary and experience.
   - **Findings:** Identified salary clusters corresponding to different experience levels, providing insights into how salary packages (in lacs per annum) vary. A cluster between 0 to 10 indicates predominant entry-level positions, while another cluster near 50 corresponds to higher salary packages for experienced professionals.
<img src="https://drive.google.com/uc?id=1DhDviTsqZ9vxABQI2gtCuYN39s51ef4x" alt="Salary and Experience" width="400" height="300">

In conclusion, the project created a valuable tool for comprehending data science job opportunities. By extracting data from the website and employing visualizations, it offered beneficial insights for professionals, job seekers, and recruiters in the dynamic field of data science. It is important to note that these insights are derived from a snapshot of data and may evolve with real-time updates.

For any feedback, feel free to contact me at rohitpaul09@gmail.com.
