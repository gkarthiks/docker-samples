FROM python:2.7
MAINTAINER Karthikeyan Govindaraj "github.gkarthiks@gmail.com"
COPY . /app
WORKDIR /app
RUN pip install --trusted-host pypi.org --trusted-host files.pythonhosted.org -r requirements.txt
ENTRYPOINT ["python"]
CMD ["app.py"]
