FROM fedora:latest
RUN yum install python3 python3-pip -y && \
    pip3 install Flask
COPY app/app.py app.py
CMD ["python3", "app.py","&"]
