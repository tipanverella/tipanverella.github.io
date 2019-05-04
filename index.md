# Hello World!

## Let me see

\[\int_{\partial \omega} = \int_{\omega}dF\]

```sql
select *
from table
where condition;
```

```python
import datetime as dt
import numpy as np
import pandas as pd

from collections import deque, Counter

home_dir = os.path.expanduser('~')

def unzip_from(source_path, destination_directory_path):
    if not os.path.exists(destination_directory_path):
        os.makedirs(destination_directory_path)
    else:
        pass
    subprocess.call(['unzip',source_path,'-d',destination_directory_path])

def unpack_file(raw_directory_path, filename):
    with open(raw_directory_path+"/"+filename,'r') as json_input:
        jf = json.load(json_input)
    return jf
```
