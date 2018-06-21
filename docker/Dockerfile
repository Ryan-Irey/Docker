FROM ubuntu:latest
MAINTAINER Ryan Irey *rlirey@iu.edu*
RUN apt-get update -y
RUN apt-get install -y python3-pip python3-dev build-essential

COPY ~/GoogleDrive/MSDS/Coursework/sp.BigDataSoftware/docker/
ENV HOME=/docker
WORKDIR ~/GoogleDrive/MSDS/Coursework/sp.BigDataSoftware/docker/


RUN pip install --no-cache-dir -r requirements.txt

CMD [ "python", "~/GoogleDrive/MSDS/Coursework/sp.BigDataSoftware/docker/hello-world.py" ]

EXPOSE 80
