FROM python:2.7
MAINTAINER Karthikeyan Govindaraj "github.gkarthiks@gmail.com"
RUN pip install --trusted-host pypi.org --trusted-host files.pythonhosted.org -r requirements.txt
COPY . /app
WORKDIR /app
ENTRYPOINT ["python"]
CMD ["app.py"]
