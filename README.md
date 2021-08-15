## Project:
### 1) Analyze Sales data of various companies across Indian states and derive critical insights using MySQL Workbench
### 2)Prepare interactive Dashboard during Microsoft Power BI
---

We begin with downloading the `db_dump.sql` file shared in the repository which contain the entire database and then import it to `MySQL Workbench`Following which a new schema `sales` is created which consist of 5 tables - `customers`, `date`, `markets`, `products`, `transactions`

![image](https://user-images.githubusercontent.com/88250882/129467306-5c1f9ac2-5661-4842-988b-239c29a67716.png)

Once the tables are created we start Data Exploration by running the following queries

`SELECT *
FROM customers`;

![Screenshot](https://user-images.githubusercontent.com/88250882/129467840-5bac54f9-128b-44c4-a94b-c48f5a2d1ddb.png)

It brings out the content of the `customers` table which has three columns- `customer_code`, `custmer_name`, `customer_type`

Next we find out the total number of customers

`SELECT count(*)
FROM customers;
`

![scrn](https://user-images.githubusercontent.com/88250882/129488325-d1e94f34-f0da-4bd1-b04d-679472efdd85.png)

Now we find out the Markets from the `markets` column

`SELECT *
FROM markets`



