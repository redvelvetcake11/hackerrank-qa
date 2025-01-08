# Write a function
![image](https://github.com/user-attachments/assets/6720f15a-cbdd-4966-85ad-8f6af0c19fc3)
## Answer
```python
def is_leap(year):
    leap = False
    
    # Write your logic here
    if year % 400 == 0:
        leap = True
    elif year % 100 == 0:
        leap = False
    elif year % 4 == 0:
        leap = True
    else:
        leap = False
    
    return leap
```
