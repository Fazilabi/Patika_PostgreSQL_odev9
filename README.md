# Patika_PostgreSQL_odev9
## [Patika.dev](https://academy.patika.dev/)


## 1. city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
`SELECT city , country FROM Country` <br>
`INNER JOIN city ON country.country_id = city.country_id;`

## 2. customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
`SELECT first_name, last_name FROM customer`<br>
`INNER JOIN payment ON customer.customer_id = payment.customer_id;`

## 3. customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
`SELECT first_name , last_name FROM customer`<br>
`INNER JOIN rental ON rental.customer_id = customer.customer_id;`
