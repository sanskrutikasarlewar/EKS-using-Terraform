#pip install flask
#pip install redis

#python app.py

#docker-compose up

#we can see the Containerized Flask application is running with Redis caching. Refresh the webpage to increase the number of times the webpage has been viewed.

#Conclusion
#In this tutorial, you have learned how to containerize a Redis Flask application using Docker Compose. We started by building a simple Python Flask application and #implemented Redis for caching. Then, we created a Dockerfile that was used to containerize the Python Flask application. We also created a `docker-compose.yml` for #adding and configuring the application’s containers as services. Finally, we launched the two containers at once using `docker-compose up` and accessing the #application on http://127.0.0.1:5000/.
