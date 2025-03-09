1 I am created new repository called 22IT039-Assignment1 in github

2 And I'm created new folder in that i am created personal.py file





![image](https://github.com/user-attachments/assets/1a5f2f31-b156-494f-96dd-3dacb73fd4d1)




3 I am created dockerfile in same path




4 i am added the personal.py file by using comment prompt in git hub






![image](https://github.com/user-attachments/assets/fe05106a-c75e-4d1f-adff-e8b630577dc7) 






![image](https://github.com/user-attachments/assets/d0421947-14bb-40f0-9739-bb618c8ef32f)





5 Likewise i am added dockerfile by using comment prompt






![image](https://github.com/user-attachments/assets/f7ba2869-bf47-4f02-8269-0b32f0226f66)





![image](https://github.com/user-attachments/assets/0686c391-e6e0-4f65-8e21-e74fb205ae04)



6 buiding image






![image](https://github.com/user-attachments/assets/2b923327-d4ff-4fea-a502-e6f85a66e4ef)




7 container
docker run -d -p 5550:5000 22it039-personal-api




![image](https://github.com/user-attachments/assets/f7f84fd5-09c9-436a-8055-85e0fff5c65d)




8 docker ps




![image](https://github.com/user-attachments/assets/64bda4c0-b0e1-451f-ba2d-74dc378eed1e)





9 localhost:5000/name




![image](https://github.com/user-attachments/assets/0ef0cd18-a78f-41ee-a15e-d55a8f95acfc)




10 localhost:5000/department




![image](https://github.com/user-attachments/assets/2e47735a-d817-44e5-899e-283c068c9d37)





11 docker hub pushed





![image](https://github.com/user-attachments/assets/f11ad7ca-ae1c-448e-b2f0-15e3b0884bd0)





12 docker is ml file is pushed





![image](https://github.com/user-attachments/assets/feaa7fc2-2051-44b2-ae18-bf9b9bddd930)





![image](https://github.com/user-attachments/assets/e12eef0e-93b4-48b3-8085-6b791aadf3bb)






![image](https://github.com/user-attachments/assets/daf373ac-42d0-4ca4-9174-f90664c3b05a)





13 in same path i am created docker-compose.yml file





my code is 



version: "3.8"

services:
  personal-api:
    image: "sathyapm1006/22it046-personal-api"
    ports:
      - "5005:5000"  
    restart: always

  personal-api-2:
    image: "meghasreek25/22it020-personal-api"
    ports:
      - "5505:5000"  
    restart: always

  ml-model:
    build:
      context: .
      dockerfile: Dockerfile-ml-model  # Ensures it builds from your Dockerfile
    image: "reenayasotha/1214214-ml-model:latest"
    ports:
      - "6000:6000"  
    restart: always
    command: ["python", "ml-model.py"]




![image](https://github.com/user-attachments/assets/36897b76-2d62-406b-874c-641507baf0a0)





![image](https://github.com/user-attachments/assets/2229c70d-76d9-4039-b4da-48da539522f6)



![image](https://github.com/user-attachments/assets/d5ecd696-f625-4cb1-95fc-4591db767168)





14 my friend image







![image](https://github.com/user-attachments/assets/438aa24b-3693-4501-ac42-b2fc584b8539)
