---

```python
class Person:
    def __init__(self):
        self.username = 'ADITHCV'
        self.name = 'Adith CV'
        self.web = null
        self.twitter = null
        self.code = {
            'frontend': ['HTML', 'CSS', 'JavaScript', 'ReactJS', 'Svelte', 'Boostrap', 'TailWind'],
            'backend': ['Python', 'PHP', 'Flask', 'Django', 'Laravel', 'NodeJS'],
            'database': ['neo4j, 'MySQL', 'SQLite3', 'Mongo DB'],
            'devops': ['Docker', 'Nginx'],
            'tools': ['GIT', 'GitHub', 'Jupyter notebook',  'Redis'],
            'misc': ['Firebase', 'GNU/Linux']
        }
        self.architecture = ['MVC','microservices']
    def __str__(self):
        return self.name
if __name__ == '__main__':
    me = Person()
```
