FROM python:3.12.2
COPY . .
RUN pip install --no-cache-dir -r requirements.txt
CMD ["python", "flask_app.py"]

# docker build -t flask-app:v1 . 
# docker run -p 5000:5000 flask-app:v1 