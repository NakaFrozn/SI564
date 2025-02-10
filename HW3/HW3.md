# Homework 3

**SUBJECT**: Week 3  
**FROM**: Zhonghan Xie  
**TO**: Raj Kumar  

Hi Raj,

THanks for your email. I've looked into the `taxdata` database to know more about the non-profits' tax data and answer your questions.

**Part 1**:

1. In the year 2014, there were 247 Ann Arbor companies in the database.
![alt text](<Screenshot 2025-02-10 at 13.20.32.png>)

2. In the year 2014, there were 20 companies making more than ten billion dollars in revenue. The companies are listed below:
![alt text](<Screenshot 2025-02-10 at 13.23.40.png>)

3. Over the years, there were 24 companies making more than ten billion dollars in revenue. The companies are listed in the terminal output below. It seems that most of the companies making more than ten billion dollars in revenue are in the year 2014.
![alt text](<Screenshot 2025-02-10 at 13.25.58.png>)

**Part 2**:

1. The top 20 companies with the most expenses in the year 2013 are listed below.
![alt text](<Screenshot 2025-02-10 at 13.30.23.png>)

1. There were 88153 companies with a revenue between $1 and $100,000 and expenses between $10,000 and $200,000 in our records. I randomly selected 20 companies from the list. Their EINs, names, cities and their revenues and expenses are listed below.
![alt text](<Screenshot 2025-02-10 at 13.34.58.png>)  
![alt text](<Screenshot 2025-02-10 at 13.38.30.png>)

**Part 3**:

1. There are 378 companies with "toy" mentioned in their purposes.
![alt text](<Screenshot 2025-02-10 at 13.43.52.png>)

2. There are 2794 companies with "smith" mentioned in their `ptname` field and with a positive revenue in our records.
![alt text](<Screenshot 2025-02-10 at 13.46.00.png>)

**Part 4**:

1. I pulled the name and the length of the names of 50 randomly selected companies with `ptid=P01345770` in the `taxdata` table.
![alt text](<Screenshot 2025-02-10 at 13.48.51.png>)

2. There are 917 companies with a `purpose` field containing less than 10 characters in our records.
![alt text](<Screenshot 2025-02-10 at 13.53.22.png>)

**Part 5**:

1. There are 52,560 employees that were hired in the years of 1990, 1994 and 1995. The shortest `WHERE` clause is `WHERE year(hire_date) IN (1990, 1994, 1995)`.
![alt text](<Screenshot 2025-02-10 at 14.01.18.png>)

2. There were 2,796 Senior Engineers in the company on 1986-06-26. The query is `SELECT count(*) FROM employees WHERE title='Senior Engineer' AND '1986-06-26' BETWEEN from_date AND to_date;`.
![alt text](<Screenshot 2025-02-10 at 14.06.20.png>)

3. There are more than 150,000 employees in our record have or once had the title containing "Engineer". Here I presented 10 randomly selected employees.
![alt text](<Screenshot 2025-02-10 at 14.12.29.png>)
![alt text](<Screenshot 2025-02-10 at 14.14.02.png>)

The data dictionaries for the tables I used above are attached as a spreadsheet in the email. Let me know if you have any additional questions.

Best,
Jonas