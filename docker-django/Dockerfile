FROM python:3.8

WORKDIR /CRUD_in_DFR

COPY ./CRUD_in_DFR /CRUD_in_DFR

RUN pip install Django==4.0.5 django-filter==22.1 djangorestframework==3.13.1 psycopg2-binary==2.9.3

ENV SECRET_KEY django-insecure-nw^y+m^wmxza1asgk+)!ua2qx9)g+#v=6%76-9i8i(ffjeo494j
ENV DEBUG 1

RUN python manage.py migrate

CMD ["python", "manage.py", "runserver", "0.0.0.0:8000","--noreload"]