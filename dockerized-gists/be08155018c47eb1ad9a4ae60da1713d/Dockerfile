FROM python:2.7.13
ADD snippet.py snippet.py
RUN ["pip", "install", "nmap"]
RUN ["pip", "install", "paramiko"]
CMD ["python", "snippet.py"]