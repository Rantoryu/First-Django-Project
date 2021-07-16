
# Running the Project Locally

## Installation

First, clone the repository to your local machine:

```bash
git clone https://github.com/Rantoryu/webapp.git
```

Activate virtual environment:
```bash
.\Scripts\activate
```

Install the requirements:

```bash
pip install -r req.txt
```

Apply the migrations:

```bash
python manage.py migrate
```

Finally, run the development server:

```bash
python manage.py runserver
```

The project will be available at 127.0.0.1:8000.
