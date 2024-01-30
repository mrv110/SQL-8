# SQL-Ödev8

1. Test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```
CREATE TABLE employee(
	id SERIAL PRIMARY KEY,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
);
```

2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```
insert into employee (name , birthday, email) values ('Lee', '1958-10-12', 'lminney0@mysql.com');
insert into employee (name , birthday, email) values ('Archibald', '1908-01-18', 'adankersley1@dot.gov');
insert into employee (name , birthday, email) values ('Arlene', '1996-09-26', 'arushmer2@army.mil');
insert into employee (name , birthday, email) values ('Casey', '1920-01-25', 'ceagle3@prnewswire.com');
insert into employee (name , birthday, email) values ('Peri', '1920-04-28', 'pfinnie4@ca.gov');
insert into employee (name , birthday, email) values ('Zuzana', '1987-01-24', 'zcousens5@flickr.com');
insert into employee (name , birthday, email) values ('Yancy', '1989-11-05', 'ygrayshan6@ucoz.com');
insert into employee (name , birthday, email) values ('Duncan', '1900-05-02', 'dwhiskerd7@engadget.com');
insert into employee (name , birthday, email) values ('Winn', '1976-04-14', 'wbickle8@slideshare.net');
insert into employee (name , birthday, email) values ('Nara', '1983-04-08', 'nnoar9@bizjournals.com');
insert into employee (name , birthday, email) values ('Eba', '1907-05-10', 'emucklestonea@t-online.de');
insert into employee (name , birthday, email) values ('Garik', '1913-11-17', 'ghounsonb@desdev.cn');
insert into employee (name , birthday, email) values ('Abigale', '1933-06-09', 'amckleodc@shop-pro.jp');
insert into employee (name , birthday, email) values ('Neale', '1947-02-03', 'nhowsleyd@rakuten.co.jp');
insert into employee (name , birthday, email) values ('Neils', '1958-05-07', 'ndorgone@i2i.jp');
insert into employee (name , birthday, email) values ('Berti', '1973-09-24', 'bortof@nhs.uk');
insert into employee (name , birthday, email) values ('Myca', '1999-08-21', 'mswinfong@is.gd');
insert into employee (name , birthday, email) values ('Armand', '1961-09-12', 'ajilkesh@harvard.edu');
insert into employee (name , birthday, email) values ('Charisse', '1976-04-16', 'cgreesti@umn.edu');
insert into employee (name , birthday, email) values ('Netty', '1995-04-30', 'nfenneyj@seattletimes.com');
insert into employee (name , birthday, email) values ('Ardra', '1964-07-08', 'astartink@hugedomains.com');
insert into employee (name , birthday, email) values ('Breanne', '1948-11-15', 'bdeboldl@flavors.me');
insert into employee (name , birthday, email) values ('Dicky', '1907-05-01', 'dsammonm@ebay.co.uk');
insert into employee (name , birthday, email) values ('Shari', '1903-03-30', 'slemarchandn@sitemeter.com');
insert into employee (name , birthday, email) values ('Becki', '1967-05-15', 'bloffelo@nymag.com');
insert into employee (name , birthday, email) values ('Peria', '1985-07-04', 'pbussonsp@alibaba.com');
insert into employee (name , birthday, email) values ('Norbie', '1997-05-12', 'nslimanq@canalblog.com');
insert into employee (name , birthday, email) values ('Giraud', '1920-06-07', 'gbrookshawr@gizmodo.com');
insert into employee (name , birthday, email) values ('Ramonda', '1947-10-22', 'rmenelawss@reuters.com');
insert into employee (name , birthday, email) values ('Arvy', '1989-02-23', 'adrejert@icq.com');
insert into employee (name , birthday, email) values ('Georgy', '1946-10-17', 'gtullu@columbia.edu');
insert into employee (name , birthday, email) values ('Jaye', '1955-05-28', 'jstittlev@uol.com.br');
insert into employee (name , birthday, email) values ('Geri', '1964-07-22', 'gyearnew@nydailynews.com');
insert into employee (name , birthday, email) values ('Jenifer', '1996-08-10', 'jmartschikx@nydailynews.com');
insert into employee (name , birthday, email) values ('Di', '1972-03-15', 'droggery@etsy.com');
insert into employee (name , birthday, email) values ('Walliw', '1908-01-17', 'wkemmettz@miitbeian.gov.cn');
insert into employee (name , birthday, email) values ('Tomlin', '1989-03-24', 'tcrees10@chron.com');
insert into employee (name , birthday, email) values ('Issy', '1974-11-13', 'iadamkiewicz11@bbc.co.uk');
insert into employee (name , birthday, email) values ('Toby', '1929-10-16', 'tlovelock12@soundcloud.com');
insert into employee (name , birthday, email) values ('Veronika', '1966-06-13', 'vtabart13@usda.gov');
insert into employee (name , birthday, email) values ('Viki', '1930-04-14', 'vsproul14@ox.ac.uk');
insert into employee (name , birthday, email) values ('Adora', '1924-02-07', 'achampley15@tmall.com');
insert into employee (name , birthday, email) values ('Javier', '1959-07-04', 'jgremain16@bravesites.com');
insert into employee (name , birthday, email) values ('Lisle', '1993-10-30', 'lligerton17@google.com.br');
insert into employee (name , birthday, email) values ('Dorette', '1966-08-07', 'dfairnie18@twitter.com');
insert into employee (name , birthday, email) values ('Robby', '1989-08-02', 'rborrie19@jalbum.net');
insert into employee (name , birthday, email) values ('Maryellen', '1910-02-03', 'mropkins1a@bbb.org');
insert into employee (name , birthday, email) values ('Alecia', '1985-03-06', 'afreathy1b@purevolume.com');
insert into employee (name , birthday, email) values ('Jessika', '1904-12-11', 'jgolds1c@amazon.co.uk');
insert into employee (name , birthday, email) values ('Mechelle', '1997-03-04', 'mgaither1d@zdnet.com');

select * from employee;
```
3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```
UPDATE employee
SET name = 'Ekin'
WHERE id = 1;

UPDATE employee
SET email = 'ekinsukusu@gmail.com'
WHERE name LIKE '%E';

UPDATE employee
SET birthday = NULL
WHERE birthday < '1990-01-01';

UPDATE employee
SET name = 'XXX'
WHERE name LIKE 'G%' AND birthday = NULL;

UPDATE employee
SET name = 'Merve',
	email = 'merve.keskn1@gmail.com',
	birthday = '1995-10-01'
WHERE id = 2;
```
4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```
DELETE FROM employee WHERE name = 'Merve';
DELETE FROM employee WHERE id = 10;
DELETE FROM employee WHERE name LIKE '%y';
DELETE FROM employee WHERE name LIKE 'A%' AND birthday = NULL;
DELETE FROM employee WHERE id = 3 OR email = '%k';
```
