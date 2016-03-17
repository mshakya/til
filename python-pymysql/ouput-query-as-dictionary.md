# Output queries as dictionary

```python 
import pymysql

conn = pymysql.connect(host='localhost',
                           user='username',
                           passwd='password',
                           db='dbname')
    
    cur = conn.cursor(pymysql.cursors.DictCursor)

    query = """SELECT a, b FROM ab_table
    WHERE c = "yes";"""

    cur.execute(query)
    out_dic = cur.fetchall()
    cur.close()
    conn.close()
```
