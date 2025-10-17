# Web Scraping Project  

This is my **first web scraping project** and my **second data science project**.  
The main goal was to scrape book data from a **static demo website** using Python.  
I made this project just for practice and revision after learning web scraping in the *IBM Data Science Professional Certificate* course.  

---

## About the Project  

I scraped data from a static website — *[Add website link here]* — which has a collection of books with their names, prices, and ratings.  
It’s a simple site made for beginners to practice web scraping safely.  

The idea was to collect that data and organize it in a clean tabular form using Python.  

---

## What I Collected  

- **Title:** Name of each book  
- **Price:** Price of the book in GBP (£)  
- **Ratings:** Star rating of the book (out of 5)  

---

## Tools I Used  

- **requests** – to send HTTP requests and get the page content  
- **BeautifulSoup** – to parse HTML and extract useful data  
- **lxml** – as a fast HTML parser  
- **pandas** – to clean and organize the scraped data  

---

## What I Learned  

- How to read and understand the structure of a webpage (tags, classes, ids)  
- Extracting specific elements using BeautifulSoup  
- Converting raw scraped data into a pandas DataFrame  
- A basic idea of how data is collected before doing analysis in real-world projects  

---

## Sample Output  

Here’s how the final data looks after scraping and cleaning:  

| Title | Price (£) | Rating |
|--------|------------|---------|
| A Light in the Attic | £51.77 | 3 |
| Tipping the Velvet | £53.74 | 1 |
| Soumission | £50.10 | 1 |

*(Sample data from the demo website — not real book info)*  

---

## Why I Made This  

I had learned web scraping a while back in the IBM Data Science course.  
To revise and get some hands-on feel again, I thought of building a small project on my own.  
Even though it’s a small one, it helped me understand the **real process of collecting raw data** that we later use for analysis.  

---

## Folder Structure  

Webscraping_project/
│

├── Webscraping_project.ipynb           # Project file in ipynb format

├── Output_data.csv                     # Scraped data

└── README.md                           # This file

├── Webscraping_project.pdf             # Project file in pdf format

---

That’s all  
It’s a small and simple project, but it gave me confidence to move ahead towards bigger real-world data projects.
