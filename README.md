```python

#!/usr/bin/python

class SoftwareEngineer(object): 

    def __init__(self):
        self.name = "oscar"
        self.working_on = "the best idea I have"
    
    def __str__(self): 
        print(f"Currently working on {self.working_on}")


me: SoftwareEngineer = SoftwareEngineer()
me.__str__()

```





