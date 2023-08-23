# dbminds

Set up a virtual environment.

```
conda create -n mindsdb
conda activate mindsdb
```

Install libraries.

```
pip install mindsdb
```

```
pip install python-magic-bin
```

```
python -m mindsdb
```

```
http://127.0.0.1:47334/editor
```

Learning Hub - TUTORIALS - Predict Home Rental Prices

```sql
CREATE DATABASE example_db
WITH ENGINE = "postgres",
PARAMETERS = {
    "user": "demo_user",
    "password": "demo_password",
    "host": "3.220.66.106",
    "port": "5432",
    "database": "demo"
    };
```