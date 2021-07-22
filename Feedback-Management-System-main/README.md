# RabbitMQAsyncTask
## Required Installations:

> pip install pika

> pip install requests

> pip install mysqlclient

> pip install PyMySQL

> pip install uvicorn

> pip install pickle

> pip install pandas

> pip install -v scikit-learn==0.24.1

> pip install fastapi

> pip install numpy

> install Erlang from : https://www.erlang.org/downloads (choose OTP 24.0 Windows 64-bit Binary File )

> install RabbitMQ from : https://www.rabbitmq.com/install-windows.html (choose rabbitmq-server-3.8.17.exe)

To start RabbitMQ server :go to rabbitMQ Command Prompt and type rabbitmq-server start (this will start RabbitMQ server)

Run the COde:
> Select upto app folder and run python producer.py (this will send the data to RabbitMQ )
                                 python consumer.py (consumer takes the data present in the RabbitMQ and will update the tag in MYSQL)
                                 


## Commands to Run file
Terminal 1
> Feedback-Management-System-main\feedbackapi-main\core :- python fastapp.py


Terminal 2
> Feedback-Management-System-main\feedbackapi-main\core :- python consumer.py

Terminal 3
> Feedback-Management-System-main\feedbackapi-main :- python manage.py makemigration

> Feedback-Management-System-main\feedbackapi-main :- python manage.py migrate

> Feedback-Management-System-main\feedbackapi-main :- python manage.py runserver 8080


 
