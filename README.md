SELECT price, item_name, average_rating
FROM superstore;
SELECT AVG(average_rating)
FROM superstore;

SELECT*FROM superstore
WHERE category="Kitchen Supplies";

SELECT AVG(price)
FROM superstore
WHERE category='Kitchen Supplies';
