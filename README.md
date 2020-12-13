# About Project - Online Bidding Web Application

## Objective  
    
In this project, we have developed Online Bidding web application - an application that helps users to sell or buy an used and newly launched products and perfomed DevOps practices such as Static code analysis, CI/CD Pipeline using veriety of tools.

## Tools/technologies used 

1. Python- 3.8.5
2. Flask- 1.1.2
3. SQLAlchemy
4. Static Code Analysis tool - sonarcloud
5. CI/CD Pipeline tool - AWS CodePipeline 

## Implementation 

* Register Seller 
* Login Seller
* Show Product
* Register Product
* Delete Product
* Update Product


## Routes

### GET

GET ALL: [http://onlinebiddingwebapp-env-1.eba-sn6gwwxd.us-east-1.elasticbeanstalk.com/show_all](http://onlinebiddingwebapp-env-1.eba-sn6gwwxd.us-east-1.elasticbeanstalk.com/show_all)
        
GET BY ID: http://onlinebiddingwebapp-env-1.eba-sn6gwwxd.us-east-1.elasticbeanstalk.com/show_all/{id}
        
### POST
POST(Seller): http://onlinebiddingwebapp-env-1.eba-sn6gwwxd.us-east-1.elasticbeanstalk.com/register 

POST(Product): http://onlinebiddingwebapp-env-1.eba-sn6gwwxd.us-east-1.elasticbeanstalk.com/show_all/addproduct  


POST(login seller): http://onlinebiddingwebapp-env-1.eba-sn6gwwxd.us-east-1.elasticbeanstalk.com/login 

### UPDATE 

PUT BY ID: http://onlinebiddingwebapp-env-1.eba-sn6gwwxd.us-east-1.elasticbeanstalk.com/show_all/{id}/update

### DELETE

DELETE BY ID: http://onlinebiddingwebapp-env-1.eba-sn6gwwxd.us-east-1.elasticbeanstalk.com/show_all/{id}

## CI/CD Pipeline steps 

- Create a pipeline using AWS CodePipeline 

- Source: from GitHub repo

- Build : AWS CodeBuild 
    - Build specifications : buildspec.yml 

- Deploy : AWS Elastic Beanstalk 

## Instruction
### Local environment
1. `python3 -m venv virt`
2. `source ./virt/bin/activate`
3. `pip install -r requirements.txt`
4. `python application.py runserver`
    
## SCreenshots 
![login screen](https://i.ibb.co/fp1CT9j/screenshot.png)

