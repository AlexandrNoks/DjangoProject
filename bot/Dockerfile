FROM python:3.11
LABEL authors="alexnoks"
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1
RUN pip install aiogram


COPY . .
CMD ["python", "bot.py"]