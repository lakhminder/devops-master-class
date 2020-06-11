FROM python:alpine3.10
WORKDIR /app 
COPY . /app
RUN pip install -r requirements.txt
EXPOSE 5000
CMD python ./launch.py

#COPY requirements.txt /app/requirements.txt
#ENTRYPOINT ["python", "./launch.py"]


#Better version with dependency as layer
#FROM python:alpine3.10
#WORKDIR /app
#COPY requirements.txt /app/requirements.txt #Only dependencies as layer
#RUN pip install -r requirements.txt
#EXPOSE 5000
#COPY . /app #Only application code as layer
#CMD python ./launch.py