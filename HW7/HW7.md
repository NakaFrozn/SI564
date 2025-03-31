# Homework 7

**FROM**: Jonas Zhonghan Xie  
**TO**: Raj  
**SUBJECT**: RE: Request from Raj

Hi Raj,

Thank you for reaching out. Hope you are doing well! I have installed the Data Grip on my laptop.

I have also designed the two normalized database schemas for the newspaper website and the library circulation system. The ERD is attached to this email. For the newspaper website, I have designed a schema with 4 tables: `Stories`, `Authors`, `Sections`, and `Comments`.

<img src="Screenshot 2025-03-23 at 1.57.14 PM.png">

For the library circulation system, I have designed a schema with 3 tables as you required: `Books`, `Patrons`, and `CirculationRecords`.

<img src="Screenshot 2025-03-23 at 1.57.29 PM.png">

For creating the backup of the `world` database, I first saved the `world` database on my personal laptop using the command:

`mysqldump -h 34.45.141.24  --port 12373 -u jonasxie-rw -p world --set-gtid-purged=OFF > mars.sql `

I created the database called `mars` on the server using the command: `CREATE SCHEMA mars;`

Then I uploaded the `mars.sql` to the server using the command: 

`mysql -h 34.45.141.24  --port 12373 -u jonasxie-rw -p mars < mars.sql`

<img src="Screenshot 2025-03-23 at 2.21.45 PM.png">

<img src="Screenshot 2025-03-23 at 2.21.20 PM.png">

Let me know if you have any additional questions about the ERDs and the backup of database. Thank you!

Best,  
Jonas


