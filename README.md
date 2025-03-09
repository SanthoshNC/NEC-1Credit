# DOCKER HUB USER NAME: meghasreek25


# 1 Commit the code in the respective files

## file name:personal-api.py

![image](https://github.com/user-attachments/assets/6d4b8f3f-a0ab-4f84-86e0-460fc6ece22f)

## Docker file creation: Dockerfile

![image](https://github.com/user-attachments/assets/1c862a9b-b49a-4ef9-b1d1-752910f1efbb)

# 2 Screenshots and commands that you used to build the docker image. Pls note the image name should be `Reg-Number-personal-api(Example: 1214214-personal-api)`

## Creating an docker image
### Command: docker build -t 22it020-personal-api .

![image](https://github.com/user-attachments/assets/21a13669-d2c2-4bd1-bed6-113a89aca314)

## Creating a docker container
### Command: docker run -d -p 5550:5000 22it020-personal-api

![image](https://github.com/user-attachments/assets/7ea0a6a8-a41b-4710-b65a-732650b51e54)

## Testing the container
### localhost:5550/name

![image](https://github.com/user-attachments/assets/7edd610f-3a3b-4bd9-917d-feb400659d38)

### localhost:5550/register_number

![image](https://github.com/user-attachments/assets/0bc414f9-42e1-434f-b4b1-e4fb6aaf41c9)

### localhost:5550/department

![image](https://github.com/user-attachments/assets/4bbb5851-1a03-45f0-a3e5-b2122260a12c)

## Pushing the image to the docker hub

### command: docker login

![image](https://github.com/user-attachments/assets/87482afe-8ce0-4379-897a-cfaeda2acc4a)

###  command: docker tag 22it020-personal-api meghasreek25/22it020-personal-api:latest

![image](https://github.com/user-attachments/assets/2c396f29-fe5a-4309-8ef0-1be67a194bba)

### command: docker push  meghasreek25/22it020-personal-api:latest
![image](https://github.com/user-attachments/assets/a34f8beb-dc3b-490e-983e-639808c61030)

### search the pushed image--command:  docker search 22it020-personal-api

![image](https://github.com/user-attachments/assets/3692e1dd-b32f-4b1d-9464-77f29be1a50d)
![image](https://github.com/user-attachments/assets/64028791-7100-4597-b91d-9a3da6d2f5b4)

# 4 Write Dockerfile for the python file `ml-model.py`. Create image and push to DockerHub `Reg-Number-ml-model(Example: 1214214-ml-model)`

## create dockerfile for ml-model.py

### file name: Dockerfile-ml

![image](https://github.com/user-attachments/assets/9811fe7b-16bb-4f82-90c9-c8629d6f424b)

## build image---command:  docker build -t 22it020-ml-model -f Dockerfile-ml .

![image](https://github.com/user-attachments/assets/7c84abf9-f69e-4171-8ca8-a5f6257adb68)

## run the docker file

![image](https://github.com/user-attachments/assets/c57ecfc7-d6fa-43a1-aa8e-f2caeae313bb)

## docker push the image to docker hub

![image](https://github.com/user-attachments/assets/e34d627f-fa68-48eb-89e9-646e697d3d0f)

![image](https://github.com/user-attachments/assets/744cc640-7f25-4bd7-8ad9-0db99dc753a6)

# 3 Get your friend's docker image and create a compose.yml and add the screenshots and commands here. Pls ensure that you tested the app correctly

## code---docker-compose.yml

![image](https://github.com/user-attachments/assets/19c655bc-6b49-43a2-a13b-6e406809fcd0)

## command: docker-compose up

![image](https://github.com/user-attachments/assets/8cfefa13-89c4-4a30-b5c6-ee204a621621)

## command: docker-compose up -d

![image](https://github.com/user-attachments/assets/affe507b-415d-457a-9e75-b2194ae85089)

## testing in localhost
![image](https://github.com/user-attachments/assets/f331e67d-95fe-44ea-bd8e-d90d480b9d91)

![image](https://github.com/user-attachments/assets/37916158-cb3e-45aa-b6f7-c424ecb2bbbf)






