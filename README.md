I have deployed a new Docker image with the below endpoints and versions which was used in the image.

FRAMEWORK USED : 
•	Docker: V19.03.0
•	Ruby: 2.5.1
•	Postgresql: 11
•	SQLite: 3.1
•	Nginx
 


I created a sample project with endpoint as /welcome/index using postgresql DB

 
GIT LINKS: 

Please find the source code in below GIT url:
https://github.com/snehaxavier04/meraki_ruby

FYI, The repo that has been given is not able to deploy using docker due to below reasons: 

1.	There is no trace of application logs. 
2.	Routing is not defined properly. 

NGINX to build

``` docker build -t Dockerfile.rails```
