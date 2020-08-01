```python
class Konradas:
    def __init__(self):
        self.craft = 'Linux System Engineer'
        self.username = 'konradasb'
        self.name = 'Konradas'
        self.technologies = {
            'frontend': [
                'HTML', 'CSS', 'JavaScript', 'VueJS'
            ],
            'backend': [
                'Python', 'Flask', 'Django', 'FastAPI'
            ],
            'database': [
                'PostgreSQL', 'MySQL'
            ],
            'devops': [
                'Ansible', 'Chef', 'Terraform',
                'GCP', 'AWS', 'VMWare'
            ],
            'tools': [
                'GIT', 'GitHub', 'Redis', 'Celery',
                'Prometheus', 'Alertmanager',
                'Opsgenie', 'StatusPage.io',
                'Grafana', 'Graylog'
            ],
        }

    def __str__(self):
        return self.name

if __name__ == '__main__':
    me = Konradas()
```
