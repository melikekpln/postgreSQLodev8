# postgreSQLodev8

test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

CREATE TABLE test (
	id int,
	name varchar(50),
	birthday DATE, 
	email VARCHAR(100)
);

Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.


insert into test (name, birthday, email) values ('Giacobo', '2000-08-16', 'gbaack0@hc360.com');
insert into test (name, birthday, email) values ('Bobby', '1933-10-07', 'bisakovic1@vk.com');
insert into test (name, birthday, email) values ('Tabby', '2007-02-06', 'tmacneely2@salon.com');
insert into test (name, birthday, email) values ('Kristoforo', '1907-09-05', 'kmalitrott3@odnoklassniki.ru');
insert into test (name, birthday, email) values ('Cass', '2020-12-08', null);
insert into test (name, birthday, email) values ('Colette', '1941-01-21', 'conion5@a8.net');
insert into test (name, birthday, email) values ('Hilary', '1965-10-25', 'hdulake6@ibm.com');
insert into test (name, birthday, email) values ('Kipp', '1937-05-01', 'kpurcell7@github.io');
insert into test (name, birthday, email) values ('Arabela', '2013-03-05', 'asarjeant8@goo.ne.jp');
insert into test (name, birthday, email) values ('Teddie', '2000-05-05', 'twychard9@yandex.ru');
insert into test (name, birthday, email) values ('Jedidiah', '2020-09-09', 'jpetrakova@dmoz.org');
insert into test (name, birthday, email) values ('Delcine', '1978-05-11', 'dguiraudb@elpais.com');
insert into test (name, birthday, email) values ('Guillermo', '1930-04-28', 'gbourdonc@a8.net');
insert into test (name, birthday, email) values ('Aura', '1959-09-17', null);
insert into test (name, birthday, email) values ('Brit', '1986-11-20', 'bscawtone@globo.com');
insert into test (name, birthday, email) values ('Gisella', '1970-02-04', 'gbirleyf@ocn.ne.jp');
insert into test (name, birthday, email) values ('Veronika', '1980-08-23', 'vraung@bigcartel.com');
insert into test (name, birthday, email) values ('Aubert', '1972-07-12', 'ahollowh@wikimedia.org');
insert into test (name, birthday, email) values ('Byram', '1907-12-25', 'bellioti@nps.gov');
insert into test (name, birthday, email) values ('Mandel', null, 'mklaggej@theguardian.com');
insert into test (name, birthday, email) values ('Brunhilda', '2009-09-03', 'blongmirek@purevolume.com');
insert into test (name, birthday, email) values ('Warner', '2017-06-25', 'wmckellochl@cloudflare.com');
insert into test (name, birthday, email) values ('Suzi', '1991-06-27', 'sblackeslandm@wikimedia.org');
insert into test (name, birthday, email) values ('Bertie', '1952-11-24', 'bprogern@whitehouse.gov');
insert into test (name, birthday, email) values ('Meir', '1986-04-13', 'msinncocko@soundcloud.com');
insert into test (name, birthday, email) values ('Onfroi', '1922-12-02', 'osharphurstp@studiopress.com');
insert into test (name, birthday, email) values ('Dix', '1965-04-24', 'dadvaniq@vkontakte.ru');
insert into test (name, birthday, email) values ('Selig', '1942-02-09', 'skinsellr@wikipedia.org');
insert into test (name, birthday, email) values ('Annabela', '2005-04-13', 'apaules@domainmarket.com');
insert into test (name, birthday, email) values ('Shepperd', '1925-08-18', 'sborrettt@hexun.com');
insert into test (name, birthday, email) values ('Bethena', '1930-07-14', null);
insert into test (name, birthday, email) values ('Hildy', '1955-12-11', 'hrumgayv@merriam-webster.com');
insert into test (name, birthday, email) values ('Noe', '1902-12-04', 'nsambrookw@indiatimes.com');
insert into test (name, birthday, email) values ('Harriott', '1983-05-03', 'hoflavertyx@sciencedirect.com');
insert into test (name, birthday, email) values ('Grady', '1960-01-14', 'gperley@un.org');
insert into test (name, birthday, email) values ('Griffie', '1937-06-14', 'gturpeyz@microsoft.com');
insert into test (name, birthday, email) values ('Carter', null, 'clemerie10@slate.com');
insert into test (name, birthday, email) values ('Arne', '1907-12-08', 'adunkerton11@utexas.edu');
insert into test (name, birthday, email) values ('Manda', '1950-09-30', 'mwornham12@naver.com');
insert into test (name, birthday, email) values ('Iormina', null, 'iskottle13@vinaora.com');
insert into test (name, birthday, email) values ('Trixy', '1991-07-24', 'tchillingsworth14@discuz.net');
insert into test (name, birthday, email) values ('Kaitlyn', '1927-05-13', 'kandreix15@hibu.com');
insert into test (name, birthday, email) values ('Lurette', '2019-02-15', 'lbricknall16@illinois.edu');
insert into test (name, birthday, email) values ('Tiena', '2022-10-28', 'tdorbin17@mozilla.org');
insert into test (name, birthday, email) values ('Burty', '1992-02-14', 'babele18@buzzfeed.com');
insert into test (name, birthday, email) values ('Dale', '1928-10-19', 'dmauchline19@princeton.edu');
insert into test (name, birthday, email) values ('Petunia', '1909-12-07', 'pgertz1a@va.gov');
insert into test (name, birthday, email) values ('Ignazio', '1905-10-12', 'iskally1b@npr.org');
insert into test (name, birthday, email) values ('Devina', '1941-12-16', 'dmassen1c@skype.com');
insert into test (name, birthday, email) values ('Archambault', null, 'avine1d@hostgator.com');


Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

UPDATE test SET name = 'melike', birthday ='2000-03-08', email = 'melikekpln19@gmail.com' WHERE name = 'Bobby';
UPDATE test SET name = 'yusuf', birthday ='2001-03-08', email = 'yusuf@gmail.com' WHERE name = 'Giacobo';
UPDATE test SET name = 'barış', birthday ='1998-03-12', email = 'baris@gmail.com' WHERE name = 'Trixy';
UPDATE test SET name = 'özlem', birthday ='1998-11-12', email = 'özlem@gmail.com' WHERE name = 'Burty';
UPDATE test SET name = 'merve', birthday ='1995-09-12', email = 'merve@gmail.com' WHERE name = 'Dale';

Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
DELETE FROM test WHERE name = 'Dale';
DELETE FROM test WHERE name = 'Arne';
DELETE FROM test WHERE name = 'Carter';
DELETE FROM test WHERE name = 'Bethena';
DELETE FROM test WHERE name = 'Lurette';
