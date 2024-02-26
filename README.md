# sqlodev12
sorgu senaryolarını dvdrental örnek veri tabanı üzerinden gerçekleştiriniz.

1-)film tablosunda film uzunluğu length sütununda gösterilmektedir. Uzunluğu ortalama film uzunluğundan fazla kaç tane film vardır?
select COUNT(*) from film where length> select AVG(length) from film;
2-)film tablosunda en yüksek rental_rate değerine sahip kaç tane film vardır?
select MAX(rental_rate) from film ;
3-)film tablosunda en düşük rental_rate ve en düşük replacement_cost değerlerine sahip filmleri sıralayınız.
select MIN(rental_rate), MIN(replacement_cost) from film;
4-)payment tablosunda en fazla sayıda alışveriş yapan müşterileri(customer) sıralayınız.
select MAX(customer) from payment;
