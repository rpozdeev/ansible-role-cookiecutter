# ansible-role-cookiecutter
Cookiecutter шаблон ansible роли с включеным molecule

# Usage
```bash
pip install cookiecutter
cookiecutter gh:rpozdeev/ansible-role-cookiecutter
```

# Requiremets
Create file ./molecule/\<scenario\>/requirements.yml
```yaml
---
- name: docker
  scm: git
  src: git+git@github.com:rpozdeev/ansible-docker.git
 version: master
```
