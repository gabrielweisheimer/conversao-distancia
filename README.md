# conversao-distancia

1. docker build -t gweisheimer/conversao-distancia:v1 .
2. docker push gweisheimer/conversao-distancia:v1
3. docker tag gweisheimer/conversao-distancia:v1 gweisheimer/conversao-distancia:latest
4. docker push gweisheimer/conversao-distancia:latest
5. docker run -d -p 5000:5000 gweisheimer/conversao-distancia:v1