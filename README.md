# build docker image 
```
docker build . -t tornado-azure:0.0.1 --progress=plain --no-cache
```

# run in local
```
docker run -it --rm -p 8000:8000 --name tornado-azure tornado-azure:0.0.1
```

# tag the image
```
docker tag tornado-azure:0.0.1 xxx.azurecr.io/tornado-azure:0.0.1
```

# push to your azure container registry
```
docker push xxx.azurecr.io/tornado-azure:0.0.1
```


