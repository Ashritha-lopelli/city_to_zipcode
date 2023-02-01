# city_to_zipcode


# for docker build 
docker build -t restapi-image .

# for running image
docker run --name restapi-container-2 -p 5003:5003 restapi-image
