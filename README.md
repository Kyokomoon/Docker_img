# Docker_img
Docker images for jenkins test

### что бы запустить билд Python Backend

```
sudo docker build -t build_python -f ./Docker_img/BUILD/Build_Python_Back .
```
### что бы запустить билд Front react

```
sudo docker build -t build_react -f ./Docker_img/BUILD/Build_front_react .
```
### что бы запустить билд Go Back

```
sudo docker build -t build_go -f ./Docker_img/BUILD/Build_Go_Back .
```

### что бы запустить билд Android
```
sudo docker build --no-cache -t build_android -f ./Docker_img/BUILD/Build_Android .
```
