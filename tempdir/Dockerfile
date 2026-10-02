FROM python:3.11
ENV PYTHONUNBUFFERED=1
RUN pip install --no-cache-dir -q  flask==2.3.3
COPY  ./static /home/myapp/static/
COPY  ./templates /home/myapp/templates/
COPY  sample_app.py /home/myapp/
EXPOSE 5050
CMD python /home/myapp/sample_app.py
