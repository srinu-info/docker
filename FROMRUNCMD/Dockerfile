#FROM:Specify base image, Every docker file starts from base image unless we created from scrach
FROM almalinux:9 

#RUN: Run commands duirng image build
RUN dnf install nginx -y

#CMD: Execute command during container creation
CMD ["nginx", "g", "daemon off ;"]

