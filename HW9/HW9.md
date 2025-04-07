# Homework 9

**FROM**: Jonas Zhonghan Xie  
**TO**: Raj  
**SUBJECT**: RE: Letter from Raj

Hi Raj,

Thanks for reaching out. I have used the following command to insert data to the NewsStores database.

```{sql}
INSERT INTO Authors (first_name, last_name, email, bio)
VALUES
    ('Jonas', 'Xie', 'jonasxie@umich.edu', 'Jonas Xie is a MPP-MSI dual degree student from UMichigan.'),
    ('Ben', 'White', 'benwhite@umich.edu', 'Ben White is a hypothetical graduate students from UMichigan.'),
    ('Kylian', 'Mbappe', 'kmbappe@gmail.com', 'Kylian is a world class football player'),
    ('Marcus', 'Rashford', 'mrashford@gmail.com', 'Marcus is a world class left-wing striker from Man Utd.'),
    ('Jude', 'Bellingham', 'jbelling@gmail.com', 'Jude is a world-wide well-known midfielder from Read Madrid.'),
    ('Pablo', 'Gavira', 'pgavi@gmail.com', 'Pablo Gavi is one of the best BBM midfielder in Barcelona.');

INSERT INTO Comments (story_id, commenter_name, content, ip_address)
VALUES 
  (1, 'Vanilla', 'Truly unexpected result!', null),
  (1, 'Zhonghan', 'Nice for Man utd, at least it was a draw.', null),
  (2, 'Lionel Zhong', 'Stupid coach for not using substitutes. We have so many key players on the bench.', null),
  (3, 'Norame', 'We will miss him. true legend.', null),
  (4, 'Economist', 'This is so stupid. It is not Chinese but American citizens going to afford those taxes.', null),
  (5, 'Kart', 'I mean.. How can we fulfill our promise for education when we don''t have the resources to support our children. Liberty of choice matters. But those grants also matter!!!', null);

INSERT INTO Sections (section_name, description)
VALUES
  ('Sports', 'News stories about sports'),
  ('Fashion', 'latest stories about fashion industry'),
  ('Politics', 'Latest political news in United States and around the world'),
  ('Arts', 'news about art industry'),
  ('Technology', 'Latest updates from STEM'),
  ('Society', 'Stories about US society');

INSERT INTO NewsStories (author_id, section_id, title, content, status, published)
VALUES
  (26, 1, 'Man Utd made draw with Man City', 'Man Utd today 1 point in match vs. Man City', 'published', '2025-04-06 22:23:33'),
  (26, 1, 'Liverpool lost key match against Fulham', 'Liverpool lost 2-3 vs Fulham which was truly unexpected.', 'published', '2025-04-06 22:24:27'),
  (26, 1, 'Kevin De Bruyne left Man City by the end of the seadon', 'Kevin announced earlier this week that he will leave Man City at the end of the season. The Belgium midfielder is a true legend in Man City and the Premier League.', 'draft', NULL),
  (27, 3, 'Trump announced reciprocal tariffs on trade partners', 'Trump administration announced new tariffs on worldwide trade partner economies this week. The administration imposes China 34% tariff, highest among the countries. China''s Ministry of Commerce said that China has filed a lawsuit with WTO''s dispute mechanism.', 'published', '2025-04-06 22:28:54'),
  (27, 3, 'Trump to abolish Department of Education', 'Trump signed executive order to dismantle Federal Department of Education this month. The action has complex implications but clearly negative impact on marginalized populations.', 'published', '2025-04-06 22:30:15');
```

As I manually inserted these rows, I know the rows in the tables are not many. So I used `SELECT *` in my queries. It is not preferred but it is for the presentations.

I randomly deleted 3 rows in `Comments` table.
![Alt text](%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20250406225313.png)

Then I updated the `commenter_name` to Karten in the last row of the table.
![Alt text](%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20250406225635.png)

Let me know if you have any additional questions.

Best,  
Jonas
