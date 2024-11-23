# Installation Guide for HOFUNS_Project  on macOS

## Overview

This guide provides step-by-step instructions for installing HOFUNS_Project on macOS.



### Online operation address: 

http://218.250.236.203/login.php



### Username and password:

**username:  admin1**

**password:  AdminTest**



## Prerequisites

- Ensure you have [Homebrew](https://brew.sh/) installed on your macOS.

## Installing PostgreSQL

1. **Install PostgreSQL using Homebrew:**

   ```bash
   brew install postgresql
   ```

2. **Start the PostgreSQL service:**

   ```bash
   brew services start postgresql
   ```

3. **Connect to PostgreSQL:**

   ```bash
   psql -U postgres
   ```

4. **CREATE ROLE root WITH LOGIN PASSWORD '12345678';**

   ```sql
   CREATE ROLE root WITH LOGIN PASSWORD '12345678';
   ```

5. **Then create a database and run the sql code according to the commands in the directory**

​		database files address:    **HOFUNS_Project - DataBase**

## Installing PHP

1. **Install PHP using Homebrew:**

   ```bash
   brew install php
   ```

2. **Start the PHP built-in server:**

   ```
    php -S localhost:8000
   ```

3. **Access your PHP file in a browser:**

   ```php
   http://localhost:8000/login.php
   ```

   php files address:  **HOFUNS_Project - htdocs_final_edition**
