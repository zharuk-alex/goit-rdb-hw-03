# goit-rdb-hw-03

**#1.1**

```
SELECT * FROM products;
```

<details>
  <summary>Screenshot</summary>

![](./images/p1_1.jpg)

</details>
<br/>

**#1.2**

```
SELECT name, phone FROM shippers;
```

<details>
  <summary>Screenshot</summary>

![](./images/p1_2.jpg)

</details>

---

**#2**

```
SELECT AVG(price) AS avg_price, MAX(price) AS max_price, MIN(price) AS min_price
FROM products;
```

<details>
  <summary>Screenshot</summary>

![](./images/p2.jpg)

</details>
<details>
  <summary>ROUND</summary>

![](./images/p2_round.jpg)

</details>

---

**#3**

```
SELECT DISTINCT category_id, price
FROM products
ORDER BY price DESC LIMIT 10;
```

<details>
  <summary>Screenshot</summary>

![](./images/p3.jpg)

</details>

---

**#4**

```
SELECT COUNT(id) AS total
FROM products
WHERE price >= 20 AND price <= 100;
```

<details>
  <summary>Screenshot</summary>

![](./images/p4.jpg)

</details>
<details>
  <summary>BETWEEN</summary>

![](./images/p4_between.jpg)

</details>

---

**#5**

```
SELECT supplier_id, COUNT(supplier_id) AS total, AVG(price) AS avg_price
FROM products
GROUP BY supplier_id;
```

<details>
  <summary>Screenshot</summary>

![](./images/p5.jpg)

</details>
