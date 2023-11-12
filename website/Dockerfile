FROM ubuntu:22.04
LABEL authors="alexnoks"

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1
RUN pip install Django

COPY . .
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]