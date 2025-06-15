# Title:


### Sub Title

------


```python
import random
import uuid

def generate_sample_data(n):
  data = []
  for i in range(n):
    record = {
        "id": str(uuid.uuid4()),
        "value": random.random()            
    }
    data.append(record)
  return data

```
