# lsml2_fp

Hello!

Please perform the following steps to start the final project:
1. Download docker image of the project [lsml2_fp](link_to_image);
2. In command prompt go to the folder with image archive and then type:
   docker load lsml2_fp.tar
3. Run container from image:
   docker run -d --rm -p 80:80 lsml2_fp:01
4. In a browser go to: localhost:80
5. If everything is correct, you will see main page of the project web-service.
   ![pic](https://github.com/DL-hackathon/lsml2_fp/blob/main/web_service.png)
