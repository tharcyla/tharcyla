```python
tharcyla = {
    "username": "tharcyla",
    "name": "Thárcyla Mourão",
    "pronouns": "she/her",
    "fun fact": "ᱬ wanda maximoff ᱬ is her favorite superhero",
    "education": {
        'data science': [['Data Analyst', 'Udacity'], ['Programming for Data Science with Python', 'Udacity']],
        'business': ['Master in Business Administration', 'Federal University of Rio de Janeiro'],
        'management': ['Strategic Management', 'Federal University of Rio de Janeiro']
    },
    "employment": {
        'project analyst': ['Studio VS', 'Rio de Janeiro, Brazil'],
        'english teacher': ['CCAA', 'Rio de Janeiro, Brazil'],
        'greeter': ['The Walt Disney Company', 'Florida, United States'],
    }
}

def iteration(user):
    for key, value in user.items():
        if type(key) is str and type(value) is str:
            print(f'{key}: {value}')
        elif type(value) is dict:
            print(f'{key}:')
            iteration(value)
        else:
            print(f'    {key}: {value}')

def main():
    iteration(tharcyla)

if __name__ == "__main__":
    main()
```