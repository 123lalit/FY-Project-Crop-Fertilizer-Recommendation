# Crop Prediction

## Step 1 : Clone Repository 
```
git clone https://github.com/codegenixtraining/crop-prediction
cd crop-prediction
```

## Step 2 : Building your image
```
docker build . -t crop-prediction
```

## Step 3 : Run the image
```
docker run -p 5000:5000 crop-prediction
```

## Step 3 : Run the application on this URL
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Home: http://localhost:5000/  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Crop Recommendation: http://localhost:5000/crop-recommend  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Fertilizer Recommendation: http://localhost:5000/fertilizer  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Disease Prediction: http://localhost:5000/disease-predict  


If you need to go inside the container you can use the exec command:
```
# Enter the container
docker exec -it <container id> /bin/bash
```


