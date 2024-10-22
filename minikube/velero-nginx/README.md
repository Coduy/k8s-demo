# nginx_video



minikube stop; minikube start --mount --mount-string=C:\TEMP\nginx-data:/mnt/data
# para comprobar que ha funciondo bien el mount: 

minikube ssh 
mount | grep /mnt/data
ls /mnt/data




