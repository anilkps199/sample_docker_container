FROM python:3.6

# Create app directory
WORKDIR /app

# Install app dependencies
COPY PythonApp/src/requirements.txt ./

RUN pip install -r requirements.txt

# Bundle app source
COPY PythonApp/src /app

EXPOSE 8080
CMD [ "python", "server.py" ]
