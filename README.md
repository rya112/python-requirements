# python-requirements

How specify the project requirements and execute

## Examples

### Example 1

A general requirements

#### Create and update requirements.txt

```bash
$ pip freeze > requirements.txt
```

#### Install

```bash
$ pip install -r requirements.txt
```

### Example 2

Requirement by environment
Both execution will run the common requirement

#### Install local requirements 

This execution will install all requirements to run de project in local environment

```bash
$ pip install -r requirements/local.txt
```

#### Install production requirements 

This execution will install all requirements to run de project in production environment

```bash
$ pip install -r requirements/production.txt
```