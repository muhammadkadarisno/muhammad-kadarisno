$ docker build -t 165610039-muhammadk-image:latest .
Sending build context to Docker daemon  3.072kB
Step 1/4 : FROM nginx:1.11-alpine
 ---> bedece1f06cc
Step 2/4 : COPY index.html /usr/share/nginx/html/index.html
 ---> 35fb0f159426
Step 3/4 : EXPOSE 80
 ---> Running in 2b76db8dddf7
Removing intermediate container 2b76db8dddf7
 ---> 25b98ef76b78
Step 4/4 : CMD ["nginx", "-g", "daemon off;"]
 ---> Running in 2d34839de022
Removing intermediate container 2d34839de022
 ---> c9928b1ddf88
Successfully built c9928b1ddf88
Successfully tagged 165610039-muhammadk-image:latest
$ 
