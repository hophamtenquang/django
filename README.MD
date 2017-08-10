# Django : Memorable things

## Model and DB:

### Field options:
- null, blank
- choices : a iterable (list or tuple) of 2 tuples
```YEAR_IN_SCHOOL_CHOICES = (
    ('FR', 'Freshman'),
    ('SO', 'Sophomore'),
    ('JR', 'Junior'),
    ('SR', 'Senior'),
    ('GR', 'Graduate'),
)```
- default, help_text
- primary_key: True or False
- unique: True or False

### Automatic primary key fields
`id = models.AutoField(primary_key=True)`
