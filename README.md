```python
tharcyla = {
    "username": "tharcyla",
    "name": "Thárcyla Mourão",
    "pronouns": "she/her",
    "fun_fact": "ᱬ wanda maximoff ᱬ is her favorite superhero",
    "education": {
        'data science': ['Programming for Data Science with Python', 'Udacity'],
        'business': ['Master in Business Administration', 'Federal University of Rio de Janeiro'],
        'management': ['Strategic Management', 'Federal University of Rio de Janeiro']
    },
    "employment": {
        'project analyst': ['Studio VS', 'Rio de Janeiro, Brazil'],
        'english teacher': ['CCAA', 'Rio de Janeiro, Brazil'],
        'greeter': ['The Walt Disney Company', 'Florida, United States'],
    }
    
}

def main():
    for key, value in tharcyla.items():
        print("{}: {}".format(key, value))

if __name__ == "__main__":
    main()
```