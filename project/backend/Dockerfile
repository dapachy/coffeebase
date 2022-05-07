FROM python:3.10.4
WORKDIR /usr/src/coffebase/backend
COPY ./server/ .
RUN pip install --no-cache-dir -r requirements.txt
EXPOSE 5000
ENV FLASK_APP=server/backend.py
CMD ["python", "-m", "flask", "run", "--host=0.0.0.0"]
