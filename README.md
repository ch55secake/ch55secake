```python

#!/usr/bin/python

class Cheesecake(object): 

    def __init__(self):
        self.name = "oscar"
        self.working_on = "the best idea I have"
    
    def __str__(self): 
        print(f"Currently working on {self.working_on}")


me: Cheesecake = Cheesecake()
me.__str__()

```





