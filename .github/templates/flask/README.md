# test Flask Application

This is a Flask application.

## Installation

From source:

```bash
git clone https://github.com/jlugao/test test
cd test
make install
```

From pypi:

```bash
pip install test
```

## Executing

This application has a CLI interface that extends the Flask CLI.

Just run:

```bash
$ test
```

or

```bash
$ python -m test
```

To see the help message and usage instructions.

## First run

```bash
test create-db   # run once
test populate-db  # run once (optional)
test add-user -u admin -p 1234  # ads a user
test run
```

Go to:

- Website: http://localhost:5000
- Admin: http://localhost:5000/admin/
  - user: admin, senha: 1234
- API GET:
  - https://localhost:5000/api/v1/product/
  - https://localhost:5000/api/v1/product/1
  - https://localhost:5000/api/v1/product/2
  - https://localhost:5000/api/v1/product/3


> **Note**: You can also use `flask run` to run the application.
