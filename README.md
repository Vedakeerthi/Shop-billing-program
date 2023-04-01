# Shop billing program

## Table of Content
  * [Demo](#demo)
  * [Synopsis](#synopsis)
  * [Appendix](#appendix)
  * [Directory Tree](#directory_tree)
  * [Features](#features)
  * [Run Locally](#run_locally)
  * [License](#license)
  * [Technology Used](#technology_used)

## Demo

![](https://github.com/Vedakeerthi/Shop_Billing_Program/blob/main/Result.png)

## Synopsis

A combination of python and sql program to bill the products based on the items purchased by the user, and the amount of each item are updated in the database, which is accessed using SQL.

This project is based on a shop, where it bills the amount of the user purchased items in the shop, here the items available in the shop are created as schemas in a database, the sql is connected with the python program using the mysql module, so based on the item available in the shop the schemas executed are : 
    * Vegetable schema
    * Fruits schema
    * Cereal schema
    * Dairy products schema
    
In the mentioned schemas along with the name of the product, the available quantity of the product in the shop, and its cost per kilogram are added, so if there is any change in the quantity or the rate or even a new record to be added or deleted then it must be made directly on the database.

## Appendix

The departmental store database and access are created in the [Grocery Shop.ipynb](https://github.com/Vedakeerthi/Shop_Billing_Program/blob/main/Grocery%20Shop.ipynb) file.

The result for this model is present in the [Result.png](https://github.com/Vedakeerthi/Shop_Billing_Program/blob/main/Result.png) file.

## Directory Tree <a name='directory_tree'></a>

```
├── Grocery Store.ipynb
├── LICENSE
├── README.md
├── Result.png
```

## Features

- Generate a bill for your store.
- Live update of your database.
- User friendly.

## Run Locally <a name='run_locally'></a>

Clone the project

```bash
  git clone https://github.com/Vedakeerthi/Shop_Billing_Program.git
```

Start the server and run the file

```bash
  python Grocery Shop.ipynb
```

## License

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/Vedakeerthi/Shop_Billing_Program/blob/main/LICENSE)

## Technology Used <a name='technology_used'></a>

<a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> &nbsp;
<a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/mysql/mysql-official.svg" alt="my_sql" width="40" height="40"/> </a> &nbsp;
