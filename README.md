# FedJobs

Contact me via https://www.linkedin.com/in/zhaojacky/

Text analytics on federal job postings. In this repo, you'll find:

- Data Scraper (API_Caller.ipynb): This notebook scrapes current federal job listings from https://www.usajobs.gov

- Job Postings (collected_data): This folder contains all the scraped job postings. I've kept them in there for ease of analysis

- Job Recommendations (TFIDF_SimilarJobs.ipynb): This notebook takes in your resume (in .txt format) and finds the top 10 job listings that match your skillset. 

- List of Resumes (resumes): This folder contains the input resume. Resume should be in .txt format. Currently, I have my outdated resume in there but you can just replace it with  another resume if you'd like.

- Analysis (Analysis.ipynb): This notebook is an ongoing work-in-progress. As I learn more about NLP, I'm using the federal jobs listings corpus as my playground to try out new NLP techniques. See my other repo on NLP @ https://github.com/iamjz/NaturalLanguageProcessing