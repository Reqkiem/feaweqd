FROM python:3.10


COPY ./crud_logistic /crud_logistic
WORKDIR /crud_logistic

RUN pip install --no-cache-dir --upgrade -r /crud_logistic/requirements.txt

RUN python manage.py

EXPOSE 6060

CMD ["python3", "-u", "stocks_products.wsgi", "--host", "0.0.0.0", "--port", "6060"]