# Web-Scraping-Data-Sciecne-Job-Listings

The primary goal is to develop an intelligent tool that streamlines data science job searches by utilizing web scraping on the Jobs website. Through the extraction of key details and the presentation of insights via visualizations, the tool aims to assist individuals in navigating the data science job market. It also keeps professionals, job seekers, and recruiters well-informed about industry trends.

**Web Scraping:**
The project began with web scraping job listings from the TimesJobs website. The Python code utilized the BeautifulSoup library to extract relevant details from the job listings, including job title, company name, skills required, posting time, location, and salary. The scraping process involved iterating through multiple pages of job listings, refining the extraction process, and handling diverse data structures on the website.

**Data Cleaning and Transformation:**
Following data extraction, the code applied techniques like strip() and replace() to organize the data systematically using the pandas library. Custom functions ensured a clean extraction of salary information, handling variations like 'Lacs,' and refining experience data for consistency. After removing duplicates, the row count reduced to 248 while maintaining 7 columns. Subsequently, by replacing empty strings with NaN and dropping rows with null values in the 'Location' column, the row count decreased to 236, maintaining the 7 columns.

**Visualization/EDA (Exploratory Data Analysis):**
Various visualizations were created to offer insights into different facets of the data science job market:

1. **WordCloud for In-Demand Skills:**
   - **Objective:** Visualize sought-after skills.
   - **Findings:** Python, SQL, Machine Learning, Data Analysis, Data Mining, and Algorithms are currently in-demand skills in the job market.
<img src="https://drive.google.com/uc?id=14qgUR28Wndm4zcMsTriNPmC_yyN4j34t" alt="WordCloud" width="400" height="300">

2. **Top 6 Cities with Most Job Openings:**
   - **Objective:** Visualize job distribution across cities.
   - **Findings:** Bengaluru/Bangalore leads with the highest number of job openings, followed by Pune, Chennai, and Mumbai, while Ahmedabad and Gurgaon are positioned at the bottom of the list.
<img src="https://drive.google.com/uc?id=1ebArDN2cNYRAS07N1oH3q1KCxDxCWRkx" alt="Top Cities" width="400" height="300">

3. **Comparison of Full-Time Jobs and Internships:**
   - **Objective:** Compare full-time jobs with internships.
   - **Findings:** 97.2% of the opportunities are full-time positions, indicating a predominant demand for full-time roles in the data science field. The remaining 2.8% consists of internship opportunities.
<img src="https://drive.google.com/uc?id=1Ejkgv1qir-6vDw22IIogvoVTz2BGzTwo" alt="Full-Time vs Internships" width="400" height="300">

4. **Top Companies Providing Internship Opportunities:**
   - **Objective:** Visualize the count of internship opportunities by company.
   - **Findings:** Maxgen Technologies emerged as the leading company providing internship opportunities.
<img src="https://drive.google.com/uc?id=1csqyw0IhHWwCxHYtaWMa5aVgLIYLIZgm" alt="Top Companies Intern" width="400" height="300">

5. **Comparison of Work from Home vs. On-Site Opportunities:**
   - **Objective:** Compare the distribution of work-from-home and on-site job opportunities.
   - **Findings:** 96.4% of jobs require on-site presence, while 3.6% offer work-from-home options, as illustrated in the pie chart.
<img src="https://drive.google.com/uc?id=1BRftwvgo6_riu0d9K23LtGIJ1eFM_amE" alt="WFH vs On-Site" width="400" height="300">

6. **Top Companies Providing Work from Home Options:**
   - **Objective:** Visualize the number of work-from-home opportunities provided by different companies.
   - **Findings:** Currently, Solay Indu Priya and MSNU Recruiters lead as the top companies providing work-from-home options.
<img src="https://drive.google.com/uc?id=1My4u62lmLPH1ZNKI8y-7RKZ74nOrF8rP" alt="Top Companies WFH" width="400" height="300">

7. **Salary Distribution Analysis:**
   - **Objective:** Visualize the distribution of salaries.
   - **Findings:** A substantial portion of salary ranges is centered around 0-10 Lacs per annum, indicating entry-level pay scales. There is a notable concentration near 30, signifying packages tailored for mid-experienced professionals, and a more pronounced cluster between 40 and 50 denotes packages offered to highly experienced professionals.
<img src="https://drive.google.com/uc?id=1WvKo_Eij-zphceFzeJK0QSrFAupgI8LB" alt="Salary Distribution" width="400" height="300">

8. **Experience Requirements Analysis:**
   - **Objective:** Visualize the distribution of required experience levels.
   - **Findings:** There is a substantial demand for individuals with 0-3, 5-8, 3-6, 2-5, 2-7, 4-7, and 0-1 years of experience in the job market. The prominence of these experience ranges implies that companies are actively seeking candidates with varying levels of expertise, from entry-level positions (0-3 and 0-1 years) to mid-level (2-5, 3-6, 2-7 and 4-7 years) and more seasoned professionals (5-8 years).
<img src="https://drive.google.com/uc?id=1-l2auJYVx-h5vk_qNWbl9bgr_4npkgES" alt="Experience Requirements" width="400" height="300">

9. **Relationship Between Salary and Experience:**
   - **Objective:** Visualize the relationship between salary and experience.
   - **Findings:** Unveiled distinct salary clusters revealing prevalent entry-level positions (0-10 Lacs p.a.) and higher packages for experienced professionals (30-50 Lacs p.a.).
<img src="https://drive.google.com/uc?id=1XiHRNvI4KmQ9c8aIiOnBuLZ3MCWWhj46" alt="Salary and Experience" width="400" height="300">

10. **Correlation Heatmap:**
   - **Objective:** To assess the correlation between salary and the required experience in the job market.
   - **Findings:** A correlation of 0.75 suggests a moderately strong positive relationship between Average Salary and Average Experience. It means that, on average, as the years of experience increase, the corresponding average salary tends to increase by a considerable amount, and vice versa.
<img src="https://drive.google.com/uc?id=1kd47tXWJsgRdlCUA3AqeERelBzNR-6zh" alt="Salary and Experience" width="400" height="300">

In conclusion, the project created a valuable tool for comprehending data science job opportunities. By extracting data from the website and employing visualizations, it offered beneficial insights for professionals, job seekers, and recruiters in the dynamic field of data science. It is important to note that these insights are derived from a snapshot of data and may evolve with real-time updates.

For any feedback, feel free to contact me at rohitpaul09@gmail.com.
