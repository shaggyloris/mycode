FROM python:3.8-slim
COPY requirements.txt /home/ubuntu/requirements.txt
RUN pip3 install -r /home/ubuntu/requirements.txt
COPY service_registry.py /home/ubuntu/service_registry.py  
WORKDIR /home/ubuntu/
CMD ["python3", "/home/ubuntu/service_registry.py"]
EXPOSE 55555
