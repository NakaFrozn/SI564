# Homework 8

**TO:** Laurence  
**FROM:** Jonas Zhonghan Xie  
**SUBJECT:** RE: Creating tables

Hi Laurence,

Thank you for your email. I have created the tables as I outlined in the ERDs. The databases for the news stories and book circulation record projects are attached as .sql files to this email.

For maintenance, I also made some changes to the tables. For the news stories project, I added a text column in the `Authors` table to include the biography information of the author.

```{sql}
alter table Authors
    add bio text null after email;
```

I also added a column to the `Sections` table to include the description of the section of stories.

```{sql}
alter table Sections
    add description text null after section_name;
```

For the book circulation record project, I added columns to the `Patrons` table to include the address (street, city, state and 5-digit zipcode) of the patron.

```{sql}
alter table Patrons
    add address varchar(255) null after email;

alter table Patrons
    add city varchar(50) null after address;

alter table Patrons
    add state char(2) null after city;

alter table Patrons
    add zip char(5) null after state;
```

Let me know if you have any additional questions about the databases.

Best,  
Jonas



