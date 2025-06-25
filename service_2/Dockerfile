FROM python:3.9-slim
WORKDIR /app
COPY . .
RUN pip install -r requirements.txt
CMD ["python", "app.py"]  # or your main Python file
EXPOSE 5000  # change if needed

