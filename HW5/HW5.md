# Homework 5

**FROM**: Jonas Zhonghan Xie  
**TO**: Lawrence Summerset  
**SUBJECT**: RE: Our new acquisition

Hi Lawrence,

Thanks for reaching out. I am happy to help you with the questions about the data of classic model store.

1. The average customer's credit limit is about $67,659. 
![Alt text](%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20250222010404.png)

2. I listed some of the customers with their phone numbers and the payments they made.
![Alt text](%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20250222010603.png)

3. The total payment amount that the customer paid us is about $69,214.
![Alt text](%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20250222011346.png)

4. The average payment that customers in New York State made is about $89,154. The average payment that customers not in New York State made is about $86,502.
![Alt text](%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20250222012052.png)

5. The average price of the items that were shipped is about $91.
![Alt text](%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20250222012242.png)

6. The employees and the name of employees they reported to is listed below.
![Alt text](%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20250222012344.png)

7. The MSRP, sticker price, markup and the first 5 letter in the text description of the items are listed below. For extracting the first 5 letters, I use `LEFT()` function in SQL. I learned this from a tutorial [here](https://www.baeldung.com/sql/extract-first-n-characters).
![Alt text](%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20250222012534.png)

8. There 14 employees who had an order in 2005.
![Alt text](%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20250222012733.png)
![Alt text](%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20250222012817.png)

9. For "total of orders", are you referring the total number of orders or the total amount of orders? The total number of orders is 19. The sum of the amount is $850,187.
![Alt text](%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20250222013417.png)

10. If you want **only** the records matched in both table, you may want to use `INNER JOIN` or `JOIN`. 

11. If you want **all** the records from the right table and the matched records from the left table, you may want to use `RIGHT JOIN` or `RIGHT JOIN`.

The relationship diagram is also attached to this email. Please let me know if you need any further information.

Best,  
Jonas