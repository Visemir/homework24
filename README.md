Create deployment with python script(need to create docker image for it first and push it to your private docker hub registry) which returns random string. 

![](https://github.com/Visemir/homework24/blob/main/image/dockerbuild.jpg)

![](https://github.com/Visemir/homework24/blob/main/image/dockerpush.jpg)

![](https://github.com/Visemir/homework24/blob/main/image/KindCreate.jpg)



Create service for it
[Deploy, Services, Ingress](https://github.com/Visemir/homework24/tree/main/kind)

Connect to service and perform requests to see python script response

Make sure that service route traffic to a different pods

![](https://github.com/Visemir/homework24/blob/main/image/pods.jpg)

![](https://github.com/Visemir/homework24/blob/main/image/browser.jpg)
