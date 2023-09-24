# kaiburr-Task-1-3-5

## Task 1 - [Rest API Using Spring-boot](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/tree/main/src/main/java/com/kalpesh/kaiburrclient)

### Screenshots

1. **lcoalhost:8080 request**

![localhost 8080](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/7ad90d86-b77b-46a5-996c-719cd62770ef)

2. **MongoDB Connection Home**

![mongo db home](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/3ffdb4be-29b7-42ef-bca5-c41a932fc7c7)

3. **Postmen API Platform - API Checks**
   * create sevrer
  
     ![postmen create request](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/4457a7a1-3769-4400-8cb2-e3eefb7284d9)

   *  get all servers

     ![postmen get all request](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/3cca0035-5750-48ea-bcae-b5b7e83d03b0)

   *  server not found 404 error
  
     ![postmen not found request](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/ebfc3fbd-437a-482a-a6e3-1f8b20008b81)

   * search server by id

     ![postmen search by id request](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/20183b14-c59f-4e5b-b69a-f39e33cf07e6)

   * search server by name

     ![postmen search by name request](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/d58893f3-1dbf-4a77-b3d2-be7c509a355e)

   * update server

     ![postmen update request](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/2abd6a2e-be83-47ae-bcb3-e5432a485752)

   * delete server

     ![postmen delete request](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/78dcb10d-b4d2-4595-9b23-f4eb57c28168)

    
## Task 3 - Create [dockerfile](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/blob/main/Dockerfile) and build docker images. Create kubernetes yaml manifests for the application

### All steps - using dockker and minikube

* minikube start --driver=docker

![image](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/caffe2d8-aed2-4ea7-b4ce-ed5183b6f9a9)

###go to the src/main/resources directory in project and open terminal and apply following command
* minikube status

![image](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/2e234545-3f93-4478-90be-92f938b08e87)

* docker build

![image](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/c6513e4d-b7c2-42e9-aa0d-e872a01020ec)

* create config.yaml file

![image](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/f335d4a6-aaff-4e4f-9659-07125fafdcb5)

* check for docker images

![image](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/bf492b2b-6b25-4c7b-b2d9-9a76301564c9)

* get kubernates config map

![image](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/5e818044-6e64-4c12-9a8e-c31b27f2ddb3)

* create docker minikube env

![image](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/3b9448f5-d7b8-4f26-b0b1-446f3b9b1cbb)

* create and then apply application.yaml

![image](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/fa2d240b-07ee-4e0f-8c05-54d86f797428)

* create and apply db-deployment.yaml

![image](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/73dc4a3b-99af-40d7-9afd-70a76cd18a8b)

* describe server svc

![image](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/0eee1d45-b758-4a74-9de1-5f2b57657507)

* get all services

![image](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/cc413994-a5e1-4c71-9ac3-2c0f9e0a0021)

* port forward to 8080

![image](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/d80e9c8a-1ead-4037-9e0e-776c40835cf5)

* get pods info

![image](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/3b04d3de-020e-41ad-adda-01e45ca7f171)



## [Task 5 - CICD pipeline for current app  using Github Actions](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/actions)

1. Build tasks completion

![image](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/b5d79966-157e-4d2d-aa1e-667a4994ef9f)

2. Deployement tasl completion

![image](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/3148510d-a486-40a4-b664-e6d5047fe57c)

3. All workflows

![CICD workflow testing](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/fa74ac42-0566-4be4-8258-4a3811bb985e)

4. Successful build and deploy to docker repository

![CICD successful build and deploy](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/d912336b-f354-4835-b50e-0ca0a1f617c5)

5. Docker repository

![docker desktop](https://github.com/kalpesh-git0/kaiburr-Task-1-3-5/assets/78799833/93f7a49d-d615-4ea2-8bc5-28811d8df8a7)


















   
