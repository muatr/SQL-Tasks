### CREATE, DROP, UPDATE, DELETE

#### 1) test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```sql
CREATE TABLE employee (
	id INTEGER,
	name VARCHAR(50) NOT NULL,
	birthday DATE,
	email VARCHAR(100)
);
```

#### 2) Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```sql
insert into employee (id, name, birthday, email) values (1, 'Ike', '2020-08-09', 'igutsell0@symantec.com');
insert into employee (id, name, birthday, email) values (2, 'Julietta', '2011-12-20', 'jhaucke1@pinterest.com');
insert into employee (id, name, birthday, email) values (3, 'Brigitte', '2012-07-24', 'btanti2@lycos.com');
insert into employee (id, name, birthday, email) values (4, 'Rachelle', '2021-04-27', 'rmcguggy3@delicious.com');
insert into employee (id, name, birthday, email) values (5, 'Drew', '2003-09-02', null);
insert into employee (id, name, birthday, email) values (6, 'Jolynn', '2002-02-01', 'jbelone5@indiatimes.com');
insert into employee (id, name, birthday, email) values (7, 'Gannie', '2009-07-23', 'gdebold6@cdbaby.com');
insert into employee (id, name, birthday, email) values (8, 'Kerrin', '2007-05-15', 'kbrownsea7@unicef.org');
insert into employee (id, name, birthday, email) values (9, 'Cosette', '2022-12-12', 'cleakner8@whitehouse.gov');
insert into employee (id, name, birthday, email) values (10, 'Frants', '2003-03-10', 'fdairton9@springer.com');
insert into employee (id, name, birthday, email) values (11, 'Cookie', '2007-03-02', 'cclemptona@miibeian.gov.cn');
insert into employee (id, name, birthday, email) values (12, 'Klemens', null, 'kmeredithb@blinklist.com');
insert into employee (id, name, birthday, email) values (13, 'Sianna', null, 'staklec@berkeley.edu');
insert into employee (id, name, birthday, email) values (14, 'Daveta', '2018-05-18', 'ddrabled@globo.com');
insert into employee (id, name, birthday, email) values (15, 'Maurits', '2013-03-02', 'mtessingtone@aol.com');
insert into employee (id, name, birthday, email) values (16, 'Linus', '2019-04-20', 'lcolombierf@craigslist.org');
insert into employee (id, name, birthday, email) values (17, 'Saw', null, 'schmielg@issuu.com');
insert into employee (id, name, birthday, email) values (18, 'Aharon', '2022-08-14', 'aweinhamh@kickstarter.com');
insert into employee (id, name, birthday, email) values (19, 'Debera', '2008-10-05', 'dhinchoni@slate.com');
insert into employee (id, name, birthday, email) values (20, 'Dasie', null, 'dmegsonj@apache.org');
insert into employee (id, name, birthday, email) values (21, 'Jennie', '2007-01-01', 'jkhomishink@ifeng.com');
insert into employee (id, name, birthday, email) values (22, 'Mureil', '2004-11-08', 'mbuntonl@livejournal.com');
insert into employee (id, name, birthday, email) values (23, 'Juana', null, 'jpickersailm@google.pl');
insert into employee (id, name, birthday, email) values (24, 'Robert', '2021-05-02', 'rkelwickn@nih.gov');
insert into employee (id, name, birthday, email) values (25, 'Elle', '2009-12-06', null);
insert into employee (id, name, birthday, email) values (26, 'Clim', '2010-09-04', 'crebillardp@github.com');
insert into employee (id, name, birthday, email) values (27, 'Chip', '2022-02-19', 'csiggensq@nature.com');
insert into employee (id, name, birthday, email) values (28, 'Shane', '2002-08-22', 'sroncar@businesswire.com');
insert into employee (id, name, birthday, email) values (29, 'Borden', '2018-10-15', 'battos@moonfruit.com');
insert into employee (id, name, birthday, email) values (30, 'Aida', '2011-10-07', 'alocalt@scribd.com');
insert into employee (id, name, birthday, email) values (31, 'Obadiah', null, 'ocapehornu@netvibes.com');
insert into employee (id, name, birthday, email) values (32, 'Cullin', '2005-02-16', 'cmalcolmv@bbc.co.uk');
insert into employee (id, name, birthday, email) values (33, 'Kasper', '2013-10-12', 'kgarrettsonw@example.com');
insert into employee (id, name, birthday, email) values (34, 'Theadora', '2010-07-31', 'talexanderssonx@apache.org');
insert into employee (id, name, birthday, email) values (35, 'Rosana', '2006-09-06', 'rredparthy@merriam-webster.com');
insert into employee (id, name, birthday, email) values (36, 'Rolando', null, 'rgamagez@samsung.com');
insert into employee (id, name, birthday, email) values (37, 'Madlen', null, 'mbortolozzi10@google.com.br');
insert into employee (id, name, birthday, email) values (38, 'Walton', '2020-01-06', 'waloshechkin11@artisteer.com');
insert into employee (id, name, birthday, email) values (39, 'Malvina', '2014-04-10', null);
insert into employee (id, name, birthday, email) values (40, 'Lainey', '2013-05-06', 'lbolle13@va.gov');
insert into employee (id, name, birthday, email) values (41, 'Emmie', '2012-04-25', 'eroberds14@addtoany.com');
insert into employee (id, name, birthday, email) values (42, 'Michell', '2003-01-31', 'mcrouse15@umich.edu');
insert into employee (id, name, birthday, email) values (43, 'Ashlan', '2009-01-18', 'acharer16@infoseek.co.jp');
insert into employee (id, name, birthday, email) values (44, 'Sonnie', '2020-01-21', 'sriditch17@jugem.jp');
insert into employee (id, name, birthday, email) values (45, 'Karalynn', '2011-03-24', 'kwandrach18@vimeo.com');
insert into employee (id, name, birthday, email) values (46, 'Elly', '2015-06-03', 'eiaduccelli19@rediff.com');
insert into employee (id, name, birthday, email) values (47, 'Mellisa', '2015-04-19', 'mkimbling1a@cpanel.net');
insert into employee (id, name, birthday, email) values (48, 'Gale', '2002-12-02', 'gspinney1b@engadget.com');
insert into employee (id, name, birthday, email) values (49, 'Marice', '2002-06-15', 'mdran1c@yolasite.com');
insert into employee (id, name, birthday, email) values (50, 'Imelda', '2021-07-30', 'ijanos1d@earthlink.net');*/
```

#### 3) Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```sql
UPDATE employee
SET name = 'Murat',
	birthday = '2003-03-14',
	email = 'mtulunisan@gmail.com'
WHERE id = 14
RETURNING *;
```

```sql
UPDATE employee
SET birthday = '2023-08-20',
	email = 'today@date.com'
WHERE name LIKE 'D%';
```

```sql
UPDATE employee
SET name = 'Today',
	email = 'updated@table.com'
WHERE birthday = '2023-08-20';
```

```sql
UPDATE employee
SET name = 'Hi',
	birthday = '2002-02-02'
WHERE email ~~* 'a%';
```

```sql
UPDATE employee
SET birthday = '2014-04-24'
WHERE id >= 14 AND name LIKE 'M%' AND email ILIKE 'm%';
```

#### 4) Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```sql
DELETE FROM employee
WHERE id > 10 AND name LIKE 'S%'
RETURNING *;
```

```sql
DELETE FROM employee
WHERE name !~~* '%r%';
```

```sql
DELETE FROM employee
WHERE birthday = '2011-12-20';
```

```sql
DELETE FROM employee
WHERE email ILIKE '%unicef%';
```

```sql
DELETE FROM employee
WHERE name !~~* 'Mur%' OR email NOT ILIKE '%mai%';
```
