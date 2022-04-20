FROM python:3
WORKDIR /usr/app/
COPY . .
#########
#########
RUN apt-get clean
##########
RUN apt-get update -y
COPY . .
CMD ["p.py"]
ENTRYPOINT ["python3"]
