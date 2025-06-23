# Patika.dev SQL Ödevi – Ödev 2

Bu proje, dvdrental veritabanı üzerinden verilen SQL sorgularının çözümünü içerir.  
Aşağıda her bir sorgu için açıklama ve SQL kodları bulunmaktadır.

## 🔹 Soru 1  
**film** tablosunda bulunan tüm sütunlardaki verileri,  
**replacement_cost** değeri 12.99'dan büyük eşit ve 16.99'dan küçük olacak şekilde sıralayınız.  
`BETWEEN ... AND` yapısı kullanılmıştır.

```sql
SELECT * FROM film
WHERE replacement_cost BETWEEN 12.99 AND 16.99;
SELECT first_name, last_name FROM actor
WHERE first_name IN ('Penelope', 'Nick', 'Ed');
SELECT * FROM film
WHERE rental_rate IN (0.99, 2.99, 4.99)
  AND replacement_cost IN (12.99, 15.99, 28.99);

db- fddle linkine buradan ulaşabilirsiniz
https://www.db-fiddle.com/f/pXhjzCQMaTEX9A2wypCsiE/0
