FROM fedora:latest
RUN yum install python3 -y
RUN pip3 install Flask
COPY app/app.py app.py
RUN python3 app.py &
